#Signup Form

This project is a user registration form built with React, Formik, and MUI (Material-UI). It includes form validation and user interface elements to create a new account and navigate to a login page upon successful submission.
Features
    Form Fields:
        Name
        Username
        Email
        Phone Number
        Password
        Confirm Password

    Validation:
        Name: Only alphabets allowed.
        Username: Must contain at least one uppercase letter, one lowercase letter, one number, and one special character.
        Password: Minimum 8 characters, cannot be the same as the username.
        Confirm Password: Must match the password.
        Email: Valid email format.
        Phone Number: Must be in the format +<country_code> <number>, with a maximum of 13 digits.

    Responsive Design:
        The form is designed to be responsive and adjusts to different screen sizes.

    Button State:
        The "SIGN UP" button is disabled and grayed out while submitting or if the form is invalid.
        The button is enabled when all form fields are valid.

    Routing:
        After successful form submission, the user is redirected to the login page.

Installation

    Clone the Repository: git clone <repository_url>

Navigate to the Project Directory: cd <project_directory>

Install Dependencies: npm install
Run the Project: bash

npm start
    Open http://localhost:3000 in your browser to view the application.

Technologies Used
    React: JavaScript library for building user interfaces.
    Formik: Library for managing form state and validation.
    Yup: Library for form validation schema.
    MUI: Material-UI for React components.
    React Router DOM: For routing and navigation.

Contributing
If you want to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Make your changes and commit them.
    Push your branch to your forked repository.
    Submit a pull request to the main repository.

License

This project is licensed under the MIT License. See the LICENSE file for more details.
