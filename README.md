# Project Setup and Run Instructions (Augmentix-Assesment)

## Prerequisites

- React
- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB (You can use MongoDB Atlas or a local instance)

## Steps to Setup and Run the Project

1. **Download the Repository:**
   - Download the zip file of the current repository provided to you.
   - Unzip the folder.

2. **Frontend Setup:**
   - Change directory to the Client:
     ```bash
     cd client
     ```
   - Install the necessary packages:
     ```bash
     npm install
     ```

3. **Backend Setup:**
   - Change directory to the Server:
     ```bash
     cd server
     ```
   - Install the necessary packages:
     ```bash
     npm install
     ```
     
 
4. **Change MongoString:**
   
     MONGO_URI="your_connection_string"
     ```
   Replace `your_connection_string` with the connection string from your MongoDB instance.


5. **MongoDB Setup:**
   - Go to MongoDB Compass (or your MongoDB Atlas dashboard).
   - Create a new database and collection.
   - Copy the connection string and paste it into the `.env` file under `MONGO_URI`.


6. **Running the Project:**
   - Start the Client:
     ```bash
     cd client
     npm run dev
     ```
   - Start the Server:
     ```bash
     cd server
     npm start
     ```

## Additional Notes

- Ensure your MongoDB server is running before starting the backend.
- The frontend will run on the web (usually `http://localhost:3000`), and the backend will run on the server (usually `http://localhost:5000`).

Feel free to reach out if you encounter any issues during setup or run.
