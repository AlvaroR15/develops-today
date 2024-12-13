# Develops today test

## Installation instructions

### Backend Setup

1. Clone the repository:
   ```bash
   git clone

2. Navigate to the backend folder:
   ```bash
   cd server

3. Install the required dependencies:
   ```bash
   npm install

4. Create a .env file in the root directory of the server folder, and add the necessary environment variables (you can ask the project maintainer for the necessary variables if they are not specified).
5. To run the backend server, use the folowing command:
   ```bash
   npm run dev
   
This will start the server using nodemon. If you want to start the server without nodemon, use:
   ```bash
   npm start
```
6. The backend should now be running at http://localhost:PORT

### Frontend Setup

1. Navigate to the frontend folder:
```bash
cd client
```

2. Install the required dependencies:
```bash
npm install
```

3. To run the frontend development server, use the following command:
```bash
npm run dev
```
This will start the Next.js development server. You can access it at http://localhost:3000.

To start the production version of the frontend, run:
  ```bash
  npm start
