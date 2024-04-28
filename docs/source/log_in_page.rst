.. _log_in_page:

Log In Page
===========

Introduction
------------

The log in page allows users to authenticate themselves in order to access the application's features and personalized content. This document provides an overview of the log in functionality using the Dart programming language.

Usage
-----

This section describes what the software does and how users interact with it:

- **Authentication:** Users can create accounts log in using their email address along with their password. The RegisterLoginManager class contains methods for signing in and registering users with Firebase Authentication. 
- **Error Handling:** The login page should handle various authentication such as incorrect username/password or network errors.
- **Navigation:** After successful authentication, users are typically redirected to the application's main dashboard or home screen.

Example Usage:

To use the login page:

1. Enter your username or email address in the corresponding input field.
2. Enter your password in the password input field.
3. Click the "Log In" button to authenticate.

Maintenance
------------

The Maintenance section describes how the software achieves its functionality and how developers can maintain and extend it:

- **Code Structure:** The Flutter framework in Dart is used to provide the login functionality. The classes and functions that are relevant are summarised as follows:
- `LoginPage`: This widget represents the UI of the login page. It includes text fields for users to input their email and password, as well as buttons for signing in with email/password, Google, and Apple.
  - `RegisterPage`: Similar to the `LoginPage`, this widget represents the UI of the registration page. It allows users to create a new account by providing their email and password.
  - `RegisterLoginManager`: This class contains methods for signing in and registering users. It handles Firebase authentication and error handling.


- **Authentication Logic:** The authentication logic is handled using Firebase Authentication. The `signIn` method in the `RegisterLoginManager` class is responsible for signing in users with their email and password. Similarly, the `signUserUp` method handles user registration.

- **Error Handling:** The login and registration processes include error handling for various scenarios, such as incorrect email/password, existing accounts, and network errors. Error messages are displayed to users to provide feedback on authentication attempts.

- **Third-party Sign-in:** Users can also sign in using third-party providers like Google and Apple. The `GoogleSignInHandler` and `AppleSignInHandler` classes manage the sign-in flow for these providers.

- **Security Considerations:** Security measures such as password validation, password hashing, and length checks are implemented to ensure the security of user accounts. Firebase Authentication is used to securely store and manage user credentials.

- **Future Improvements:** Considerations for future improvements may include enhancing the user experience, implementing additional authentication methods, and optimizing code performance.


