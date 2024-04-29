.. _profile_page:

===================
Profile Page Folder
====================

Usage
======

The `profile_page` folder contains files related to user profile management, including `profileManager.dart`, `profile_page.dart`, `userManager.dart`, and `userModel.dart`.
The files are incharge of displaying user profile information and allowing users to update their details.

Mintenance
===========

profileManager.dart
--------------------

The `profileManager.dart` file has featuress for managing user profile data. It includes the following functionalities:

- **checkInputLength(input: String):** Checks if the length of the input string is within a specified limit.
- **storeUserDetails(user: UserModel):** Stores user details in the Firestore database.
- **getUserDetails():** Retrieves user details from the Firestore database.
- **deleteUserDetails():** Deletes user details from the Firestore database.




