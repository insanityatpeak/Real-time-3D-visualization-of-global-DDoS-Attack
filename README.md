# Real-time-3D-visualization-of-global-DDoS-Attack
DDOSn't Matter is a real-time 3D DDoS attack visualizer built with Next.js, Three.js, and NestJS. It maps global attacks on an interactive globe, features live analytics, filtering, and a clean architecture with Dockerized deployment.
🛠️ Prerequisites

Ensure you have the following installed:

Docker: Install Docker

Docker Compose: Install Docker Compose

🚀 Running the Project with Docker

Clone the Repository

git clone https://github.com/nkardas/ddosnt-mater.git
cd ddosnt-mater


Set Up Environment Variables

Copy the example environment file:

cp .env.example .env


Edit the .env file to configure any necessary environment variables.

Build and Start the Containers

Use Docker Compose to build and start the application:

docker-compose up --build


This command will:

Build the Docker images for the frontend and backend.

Start the containers defined in the docker-compose.yml file.

Access the Application

Once the containers are up and running, you can access the application:

Frontend: Open your browser and navigate to http://localhost:3000.

Backend: The backend API will be accessible at http://localhost:4000.

🧪 Running Tests

To run the tests for the project:

docker-compose exec backend npm test


This command will execute the tests defined in the backend service.

🧹 Stopping and Cleaning Up

To stop the running containers:

docker-compose down


To remove all containers, networks, and volumes defined in the docker-compose.yml file:

docker-compose down --volumes
