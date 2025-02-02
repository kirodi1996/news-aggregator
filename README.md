# News Aggregator App

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://reactjs.org/docs/create-a-new-react-app.html). Follow the instructions below to get started with development or to run the app in a Docker container.

## Available Scripts

In the project directory, you can run the following commands:

### `npm start`

Runs the app in development mode:

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
- The page will reload if you make edits.
- You will also see any lint errors in the console.

### `npm run build`

Builds the app for production:

- The build files will be placed in the `build` folder.
- React will bundle the app in production mode and optimize for the best performance.

---

## Running the Project in Docker

To run the app in a Docker container, follow these steps:

### Prerequisites

Before running the project in Docker, ensure you have the following installed:

- Docker (latest version recommended)

### Steps to Run the Project in Docker

1. **Clone the Repository**  
   If you haven't already, clone the project repository:

   ```bash
   git clone https://github.com/your-username/news-aggregator.git
   cd news-aggregator

2. **Build the Docker Image**

    docker build -t news-aggregator .

3. **Run the Docker Container**

    docker run -p 3000:3000 --name news-aggregator-container news-aggregator
