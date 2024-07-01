##  Airline-Management

***If you are testing the website, go (To test the website, please follow these guidelines:) in the Development steps of this README.md file***

This repository showcases a web application built using the MERN stack, which includes:

**MongoDB**: A NoSQL database for storing application data.

**Express.js**: A web application framework for Node.js.

**React.js**: A JavaScript library for building user interfaces.

**Node.js**: A JavaScript runtime for server-side programming.

The application leverages Node.js as the server powered by a MongoDB database. 


#

Below are some key interfaces of the application.

***Main page of the web application***

# ![Screenshot (8)](https://github.com/Deviprasad0815/Airline-Management/assets/131675492/d26c0604-1cf2-4f18-b8f7-8899da728958)

***Sign up page***

# ![Screenshot (16)](https://github.com/Deviprasad0815/Airline-Management/assets/131675492/6f86e50c-9613-4dce-b9d7-010aca3f4769)

***Search flights page***

# ![Screenshot (12)](https://github.com/Deviprasad0815/Airline-Management/assets/131675492/f5c087e5-7bf2-4c09-b2a2-838a70b18a98)

***Seat Reservation page***

# ![Screenshot (13)](https://github.com/Deviprasad0815/Airline-Management/assets/131675492/e1ea75d7-3be4-455a-ba35-78863ff459b1)

***User profile page***

# ![Screenshot (17)](https://github.com/Deviprasad0815/Airline-Management/assets/131675492/5b45771c-78a7-4a58-bfac-845d657f0a34)

# Development steps



***To get the website up and running, please follow these steps: ( in VS code )***

1. **Clone the repository:**
   - Begin by cloning the repository to your local machine.
   - You will find two main folders: `frontend` and `backend`.

2. **Set up the backend:**
   - Open a terminal and execute the following commands:
     ```
     cd backend
     npm install
     npm start
     ```
   - Confirm that the backend is running.

3. **Set up the frontend:**
   - Open a new terminal and run these commands:
     ```
     cd frontend
     npm install
     ```
   - If you encounter any errors, try:
     ```
     npm install --legacy-peer-deps
     ```
   - Then start the frontend:
     ```
     npm run start
     ```
   - Verify that the frontend is running.

Now, the website should be operational on your local computer, and you can proceed with testing.

#

***Explore the key features of the website:***

1. **User Registration:**         Sign up is required for booking flights.

2. **Flight Search:**             Search for flights by destination, date, and preferences.

3. **Flight Selection:**          Choose from a list of available flights based on your search criteria.

4. **Booking Process:**           Seamlessly go through seat selection, traveler details, review, and payment.

5. **Ticket Retrieval:**          Post-payment, locate your flight ticket in the profile section.

6. **E-Ticket Access:**           View and manage your e-tickets in your profile, with options to share and download.

#

***To test the website, please follow these guidelines:***

1. **Login Credentials:**
   - Use the following details to log in OR you can sign up with your own mail ID:
     - **Email:** john@gmail.com
     - **Password:** John@123

2. **Flight Search:**
   - Since the database contains a limited number of flights, please use the following routes and dates for testing:
     - Guwahati to Delhi on June 20
     - Chennai to Mumbai on June 21
     - Kolkata to Bangalore on June 22
     - Visakhapatnam to Hyderabad on June 22
    
3. Begin by selecting your preferred seat, ensuring your comfort throughout the flight. Next, enter your traveler details to personalize your journey. Review all the information to ensure everything is in order before proceeding to the payment simulation. Since this is a mock-up, there’s no actual transaction—simply navigate back to find your ticket securely saved in your profile, ready for your upcoming adventure!
