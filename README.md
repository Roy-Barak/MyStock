# MyStock Application (Main Repository)

This is the main repository for the MyStock application, which consists of two submodules:

- **Frontend**: Built using React to provide the user interface for interacting with the backend.
- **Backend**: Built using Flask to handle user authentication, portfolio management, and stock market data management.

## Setup Instructions

To set up and run the MyStock application locally, follow these steps:

### 1. Clone the Repository

First, clone this main repository, which includes both the frontend and backend as submodules:

- **`git clone --recurse-submodules git@github.com/MyStock-Website.git`**
- **`cd MyStock-Website`**

If you forget to use `--recurse-submodules` when cloning, you can initialize the submodules manually with:

- **`git submodule update --init --recursive`**

### 2. Set Up the Backend

Navigate to the `Backend/` directory and follow these steps to set up the backend:

- **`cd Backend`**

#### Create a virtual environment and activate it:

- **`python3 -m venv .venv`**
- **`source .venv/bin/activate`**

#### Install the dependencies:

- **`pip install -r requirements.txt`**

#### Set up environment variables:

Copy the `.env.example` file to `.env` and configure it with your MongoDB credentials and any other environment-specific values:

- **`cp .env.example .env`**

#### Run the Flask application:

- **`flask run`**

The backend will now be running locally. You can access it by navigating to `http://127.0.0.1:5000/` in your browser.

### 3. Set Up the Frontend

Navigate to the `Frontend/` directory and follow these steps to set up the frontend:

- **`cd Frontend`**

#### Install the dependencies:

- **`npm install`**

#### Start the development server:

- **`npm start`**

The frontend will now be running locally. You can access it by navigating to `http://localhost:3000/` in your browser.

### 4. Running the Full Application

At this point, you should have both the frontend and backend running locally.

- **Frontend**: `http://localhost:3000/`
- **Backend**: `http://127.0.0.1:5000/`

You can interact with the application via the frontend, which communicates with the backend for data and user management.

## Contributing

Feel free to open issues and submit pull requests.

**All rights reserved for Roy Barak**
