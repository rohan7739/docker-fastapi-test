# docker-fastapi-test 
## Assignment

Thank you for the opportunity to demonstrate my skills through this assignment. I truly appreciate the chance to contribute and showcase my expertise. I look forward to any feedback you may have and am excited about the possibility of working together.

## Step 1: Create Dockerfile and docker-compose file
  In the project root directory, create Dockerfile and docker-compose.yml files.

## Step 2: Build and Run the Application with Docker Compose
  In the project root directory, use Docker Compose to build and start the application.<br />
- ### docker-compose up --build


## Step 3: Access the Application
  - Swagger UI: Open http://localhost:8000/docs to view and test the API endpoints.<br />
  *Endpoints:*
  - GET /: Returns a welcome message.
  - GET /users: Returns a list of users stored in users.json.
  - POST /users: Accepts JSON data and stores it in users.json.

## Step 4: Test Data Persistence
1. Use POST /users in the Swagger UI to add a user.
2. Stop and remove the container:<br />
   - ### docker-compose down
3. Restart the container:<br />
   - ### docker-compose up
4. Go to GET /users to check that the previously added data is still present.

# conclusion
While Container is destroyed and recreate another one then **data is lost and data is not present** .....
