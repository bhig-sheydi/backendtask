# HNG12 Stage 0 Backend Task – Public API

## Project Description
This is a simple public API built with **Node.js and Express.js** for the HNG12 Backend Task (Stage 0). It returns basic information such as:
- My registered email address.
- The current datetime in **ISO 8601 format (UTC)**.
- The **GitHub repository URL** for this project.

## Live API URL
You can access the live API here:
🔗 **[https://backendtask-sigma.vercel.app/](https://backendtask-sigma.vercel.app/)**  


## How to Run Locally
Follow these steps to run the project on your local machine:

### 1. Clone the Repository
```sh
git clone https://github.com/bhig-sheydi/backendtask.git
cd backendtask
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Start the Server
```sh
node index.js
```
The server will start on **http://localhost:3000/**.

## API Documentation

### Endpoint: GET /
📌 **Request:**  
```sh
GET https://backendtask-sigma.vercel.app/
```

📌 **Response (200 OK):**  
```json
{
  "email": "bhigsheydi@gmail.com",
  "current_datetime": "2025-01-30T09:30:00.000Z",
  "github_url": "https://github.com/bhig-sheydi/backendtask"
}
```

## Tech Stack Used
- **Node.js** (Backend)
- **Express.js** (Web framework)
- **Vercel** (Deployment)

## Deployment Instructions
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Deploy the project:
   ```sh
   vercel
   ```

## Useful Link
[🔗 Node.js Developers](https://hng.tech/hire/nodejs-developers)

