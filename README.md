
# README: Table Reservation Microservice

### Overview
This microservice is designed to provide:
 **Table Reservation** – Ensures smooth reservation management, including real-time confirmation, table assignment, and verification of customer details.

### Prerequisites
- Install **Docker Desktop** in your local environment.
- Create a **MongoDB Cluster** for storing and retrieving customer and menu-related data.

### Steps to Execute the Microservice

1. **Clone the Application**
   - Clone the repository to your local machine

2. **Create MongoDB Cluster**
   - Set up a MongoDB cluster on MongoDB Atlas or any other cloud service.
   - Import the files from the `DB` folder into the MongoDB cluster.
     - Use MongoDB's import tool or MongoDB Atlas's data import features.
   - After importing, retrieve the connection string for your MongoDB cluster.

3. **Configure the Application**
   - Open the `app.js` file located in the root directory of the cloned repository.
   - Paste the MongoDB connection string at the location marked:"Add the database URL here"


4. **Run the Application using Docker**
   - Open a terminal in the application's root directory.
   - Build and run the Docker container with the following command: docker run -p 3000:3000 taske
 

5. **Access the Microservice**
   - The application should now be running on `http://localhost:3000](http://localhost:3000/make_reservation.html`


