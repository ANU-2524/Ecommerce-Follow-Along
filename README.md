# 📌 Project Name: E_Commerce_Follow_Along

## 🚀 Overview
This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

## 📚 Table of Contents
- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Milestones](#-milestones)
  - [Milestone 1: Project Setup](#milestone-1-project-setup)
  - [Milestone 2: Frontend & Backend Initialization](#milestone-2-frontend--backend-initialization)
  - [Milestone 3: Backend Structure & Server Setup](#milestone-3-backend-structure--server-setup)
  - [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)
  - [Milestone 5: Sign-Up Page & Form Validation](#milestone-5-sign-up-page--form-validation)
- [How to Run the Project](#-how-to-run-the-project)
- [Next Steps](#-next-steps)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🛠 Tech Stack
- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- File Uploads: Multer
- Version Control: Git, GitHub

---

## 📌 Milestones

### Milestone 1: Project Setup
*✅ Goals:*
- Created and updated README.md file.
- Initialized GitHub repository for version control.

---

### Milestone 2: Frontend & Backend Initialization
*✅ Goals:*
1. *Project Folder Structure:* Organized files into separate frontend and backend directories.
2. *React Frontend Setup:* Initialized a React application for building the user interface.
3. *Node.js Backend Setup:* Set up a simple Node.js server for API integration in future milestones.
4. *Tailwind CSS Configuration:* Integrated and configured Tailwind CSS for modern, responsive styling.
5. *Login Page Development:* Created a login page with functionality and styling.

---

### Milestone 3: Backend Structure & Server Setup
*✅ Goals:*
1. *Backend Folder Structure:* Created a structured hierarchy for organizing routes, controllers, models, and middleware.
2. *Server Setup:*
   - Used Node.js and Express.js to create a backend server.
   - Configured the server to listen on a designated port.
3. *Database Connection:*
   - Integrated MongoDB for efficient data storage.
   - Confirmed the connection between the server and MongoDB.
4. *Error Handling:*
   - Provided clear error messages for better debugging and user feedback.

---

### Milestone 4: Creating User Model and Controller
*✅ Goals:*
1. *User Model:* Defined the structure of user data with attributes like name, email, password, and profile picture.
2. *User Controller:* Handled user-related actions such as registration and data retrieval.
3. *Multer Integration:* Enabled file uploads for storing user profile pictures.
4. *API Routes:* Created endpoints for user creation and fetching user details.
5. *README Update:* Documented progress and updated repository.

---

### Milestone 5: Sign-Up Page & Form Validation
*✅ Goals:*
1. *Sign-Up Page UI:* Designed a clean and user-friendly sign-up form with fields for name, email, and password.
2. *Form Validation:*
   - Ensured the email follows the correct format.
   - Implemented password security criteria (minimum length, special characters, etc.).
3. *User Registration Flow:* Integrated frontend form submission with the backend API.
4. *Error Handling:* Displayed validation errors to users in real-time.
5. *README Update:* Documented progress and updated repository.

---

 ### Milestone 6: Secure User Registration
*✅ Goals:*
1. *Password Encryption:*
   - Used bcrypt to hash passwords before storing them in the database.
   - Ensured no plaintext passwords are stored.
2. *Secure Data Storage:*
   - Stored the user's encrypted password along with other necessary details in MongoDB.
3. *Updated API Endpoints:*
   - Modified the user registration endpoint to handle password hashing securely.
4. *Security Compliance:*
   - Followed best practices for protecting user credentials.
   - Complied with security standards like GDPR and PCI-DSS.
5. *README Update:*
   - Documented progress for Milestone 6 and updated the repository.

---

### 🏆 Milestone 7: Secure Login with Password Verification
- Developed a *backend endpoint* for user login.
- Implemented *user authentication* by validating credentials.
- Used *bcrypt* to compare hashed passwords securely.
- Ensured compliance with *security standards* like GDPR and PCI-DSS.
- Returned appropriate error messages for *invalid credentials*.
- Updated the *README.md* file with progress details.
- Committed and pushed changes to the *GitHub repository*.


---

### 🏆 Milestone 8: Product Card Component and Homepage Design
- Designed a *reusable Product Card Component* to display product details.
- Implemented *props* to pass product information dynamically (e.g., name, price, image).
- Used *array mapping* to display multiple products efficiently.
- Designed a *structured homepage layout* with a clean and visually appealing UI.
- Ensured *responsiveness* using CSS Grid or Flexbox.
- Updated the *README.md* file with progress details.
- Committed and pushed changes to the *GitHub repository*.

---
### 🏆 Milestone 9: Product Form Creation
✅ Goals:

- Product Form: Developed a product form for adding products with multiple images.
- Admin Access (Optional): Experimenting with adding admin-specific upload functionality.
- User Profiles (Optional): Considering adding shop-specific user roles for uploading products.
- Next Steps: Implement role-based access, improve validation, and optimize image upload.



## ▶ How to Run the Project
1. Clone the repository:
   bash
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git
   cd E_Commerce_Follow_Along
   
2. Install dependencies for both frontend and backend:
   bash
   cd frontend && npm install
   cd ../backend && npm install
   
3. Run the backend server:
   bash
   npm start
   
4. Run the frontend application:
   bash
   cd frontend
   npm start
   
5. Open http://localhost:3000/ in your browser.

---



