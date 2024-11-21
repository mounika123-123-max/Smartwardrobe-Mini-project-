# SmartWatdrobe Website 

## Description

The Wardrobe Management System is a comprehensive application designed to manage wardrobe items effectively. Users can upload, categorize, and receive personalized outfit suggestions for various occasions through an integrated chatbot. It includes user authentication (registration and login), profile management, and secure configuration using environment variables. The system supports both Node.js and Python-based logic for flexibility.

## Features

- **User Authentication**:
  - Registration and login pages for secure access.
  - User data securely managed in `users.json`.
- **Image Management**:
  - Upload and categorize wardrobe items with resizing functionality.
  - Routes for uploading images (`upload.js`) and authentication (`auth.js`).
- **Chatbot Integration**:
  - Intelligent outfit suggestions for occasions, seasons, and events.
  - Logic implemented in `chatbot.js`.
- **Profile Management**:
  - Dedicated `profile.html` page for managing user settings and wardrobe preferences.
- **Cross-Platform Logic**:
  - Backend logic using `app.js` (Node.js) and `app.py` (Python).
- **Environment Configuration**:
  - `.env` file for storing sensitive configurations.
- **Local and Global Dependencies**:
  - Separate `package.json` files for the main project and the `uploads` directory.

## Project Structure

```
Wardrobe-Management-System/
├── public/
│   ├── css/
│   │   ├── styles.css         # General styles for the application
│   │   ├── styles1.css        # Additional styles for authentication pages
│   ├── js/
│   │   ├── scripts.js         # Main JavaScript logic for frontend interactions
│   │   ├── resize-upload.js   # Logic for resizing images during upload
│   ├── index.html             # Homepage for wardrobe management
│   ├── register.html          # Registration page for new users
│   ├── login.html             # Login page for existing users
├── uploads/
│   ├── .env                   # Environment variables for secure configuration
│   ├── app.js                 # Main application file for Node.js
│   ├── app.py                 # Python-based application logic (if applicable)
│   ├── chatbot.js             # Chatbot logic for outfit suggestions
│   ├── package.json           # Project dependencies for uploads directory
│   ├── profile.html           # User profile page for managing account settings
│   ├── server.js              # Backend server file for handling requests
│   ├── server1.js             # Alternative backend server file
│   ├── users.json             # JSON file for storing user data
├── server/
│   ├── server.js              # Main backend server file
│   └── routes/
│       ├── auth.js            # Route for authentication (login and registration)
│       ├── upload.js          # Route for handling image uploads
├── .gitignore                 # Files to ignore in the repository
├── package.json               # Project dependencies and scripts
├── README.md                  # Documentation for the project
└── LICENSE                    # License information (if applicable)
```

## Installation and Usage

1. **Clone the Repository**  
   ```bash
   https://github.com/mounika123-123-max/Smartwardrobe-Mini-project-.git
   ```

2. **Navigate to the Project Directory**  
   ```bash
   cd Wardrobe-Management-System
   ```

3. **Install Dependencies**  
   Install dependencies for both the main project and the `uploads` directory:  
   ```bash
   npm install
   cd uploads
   npm install
   cd ..
   ```

4. **Environment Configuration**  
   Create a `.env` file in the `uploads` directory to set up your environment variables.

5. **Start the Server**  
   Start the Node.js backend server:  
   ```bash
   npm start
   or
   node server.js
   ```

6. **Access the Application**  
   Open your browser and go to:  
   ```bash
   http://localhost:3000
   ```

7. **Features Overview**:
   - **Register and Login**:
     - Use `register.html` and `login.html` for authentication.
   - **Manage Wardrobe Items**:
     - Upload images via `upload.js` and organize them into categories.
   - **Chatbot Suggestions**:
     - Access personalized recommendations through `chatbot.js`.
   - **Profile Management**:
     - Update account settings and preferences using `profile.html`.

