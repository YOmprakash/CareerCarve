
## Tech Stack

- **Frontend:**
  - React.js
  - Tailwind CSS
  - React Router

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v14+)
- npm (v6+)
- MongoDB

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/YOmprakash/CareerCarve.git
   ```

2. **Install dependencies for both frontend and backend:**

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. **Set up environment variables:**

   - Create a `.env` file in the `backend` directory with the following content:

     ```bash
     PORT=5000
     MONGODB_URI=<your_mongodb_uri>
     
     ```

   - Optionally, you can set up environment variables for the frontend (e.g., API base URL).

4. **Run the application:**

   - **Frontend:**

     ```bash
     cd frontend
     npm run dev
     ```

   - **Backend:**

     ```bash
     cd backend
     npm start
     ```

   - Visit `http://localhost:5000` in your browser to view the application.

## Frontend

### Folder Structure

The frontend is structured as follows:

```
frontend/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   ├── index.js
│   ├── ...
│
└── ...
```
## Backend

### Folder Structure

The backend is structured as follows:

```
backend/
│
├── models/
│   └── Mentor.js
│
│
│
└── server.js
```



### Environment Variables

In the `.env` file:

```bash
PORT=5000
MONGODB_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
```

## Deployment

To deploy the application, you can use services like render for the backend and Vercel or Netlify for the frontend. Make sure to set up environment variables in the deployment environment.

#
