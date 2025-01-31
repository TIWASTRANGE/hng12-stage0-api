# hng12-stage0-api
## Project Description
This is a simple public API built with Node.js and Express.js for the HNG12 Stage 0 task. It returns basic information in JSON format, including:
Your registered email address

The current datetime in ISO 8601 format

The GitHub URL of this project

## Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/TIWASTRANGE/hng12-stage0-api.git
cd hng12-stage0-api

2️⃣ Install Dependencies
npm install

3️⃣ Set Up Environment Variables
Create a .env file in the project root and add:
EMAIL=my-email@gmail.com
GITHUB_URL=https://github.com/TIWASTRANGE/hng12-stage0-api
PORT=3000

4️⃣ Run the Server Locally
Start the server using nodemon:
npx nodemon index.js

The API will be available at:

http://localhost:3000

## API Documentation
📌 Endpoint: 
GET /

📌 Request Format:
No authentication or request body required.

📌 Response Format (200 OK):
json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/TIWASTRANGE/hng12-stage0-api"
}

## Deployment
The API is deployed at:

<your-deployed-url>
  
## Useful Links
Hire Node.js Developers: https://hng.tech/hire/nodejs-developers
GitHub Repository: https://github.com/TIWASTRANGE/hng12-stage0-api
