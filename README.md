# Basic Authentication System

This is a basic authentication system built with Node.js, Express.js, and Passport.js. It provides user registration, login, and logout functionalities with local authentication using email and password.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/RAKHEEBAHMAD/Basic-Authentication-System/

2. Clone the repository:

   ```shell
   npm install


# Basic Authentication System
- Home Page: Accessible at the root URL. If the user is authenticated, their name will be displayed.

- Login Page: /login URL. Allows users to log in with their credentials.

- Signup Page: /signup URL. Allows new users to create an account.

- Logout: /logout URL. Allows logged-in users to log out.

# Authentication
- The system uses local authentication with email and password.

- User passwords are securely hashed using bcrypt.

- User information is stored in memory (not persistent) in the users array.

- Passport.js is used for authentication and session management.

# Acknowledgments
- Node.js
- Express.js
- Passport.js

# Flowchart
<a href="https://drive.google.com/drive/folders/16o_jSCE0Cg3efB5_OBCJXZNNYWk9UCYt">
    <img src="AUthentication System.jpg" alt="flowchart" width="500" height="700">
</a>
