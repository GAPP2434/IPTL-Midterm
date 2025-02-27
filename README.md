# IPTL Midterm Hands On Exam

# SM SuperMalls

## Description
A web application that allows the sign up and login of users using MongoDB and Node.js as well as
Javascript and the many modules used. It also has Authentication which gives the users token which is checked when logging in.

## Developer Information
- **Name:** Gio Alexander P. Petalcurin
- **Course:** IPTL
- **Section:** BSIT 3-1
- **Date Created:** February 27, 2025

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token), bcrypt.js

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/GAPP2434/IPTL-Midterm.git
    ```
2. Navigate to the project directory:
    ```bash
    cd IPTL-Midterm
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    MONGO_URI=mongodb://localhost:27017/usersDB
    JWT_SECRET=lebronjamesmygoat