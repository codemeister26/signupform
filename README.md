# signupform
# Signup Form with Phone Number Validation
 This project is a React-based signup form that includes phone number validation with dynamic country code and flag display. It uses Formik for form management, Yup for validation.
# Features
Form validation using Formik and Yup
Dynamic phone number input with country code and flag using react-phone-input-2
Password visibility toggle
Responsive layout

# Installation

# To run this project locally, follow these steps:

# Clone the repository:
# Copy code
git clone https://github.com/2605-Nishant/signupform.git
cd signupform
# Install the dependencies:
npm install
# Usage
To start the development server:
npm start
Open http://localhost:3000 to view the app in the browser.

# Project Structure
src/Signup.jsx: Main component containing the signup form
src/index.js: Entry point of the application
# Dependencies
react: Frontend library
formik: Form management library
yup: Validation library
@mui/material: Material-UI components
react-phone-input-2: Phone number input with country code and flag
# Validation Schema
# The validation schema is defined using Yup and includes:
Name: Only alphabetic characters are allowed.
Email: Must be a valid email format.
Phone: Must be a valid international number.
Username: Must contain at least one uppercase letter, one lowercase letter, one number, and one special character.
Password: Must be at least 8 characters long and not the same as the username.
Confirm Password: Must match the password.

# How to Customize
You can customize the form styles and validation schema as needed. The styles are defined inline and can be moved to a CSS file if desired.

