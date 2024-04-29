.. _profile_page:


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


profile_page.dart
------------------

The `ProfilePage` widget, which enables users to view and edit their profile information, is implemented by the `profile_page.dart` file. It consists of the following elements:

- **TextEditingController:** this is the controllers for input fields such as username, age, first name, last name, food restriction, and bio.

- **GlobalKey<FormState>:** This Key is for form validation.

- **ProfileManager:**  Instance for managing user profile data.

- **currentUser:** Instance of `UserModel` to store the current user's data.

- **_loadUserDetails():** Method to load user details from Firestore.

- **_buildProfileImage():** Method to build the profile image widget.

- **_buildInfoItem(label: String, key: String):** Method to build an individual profile information item.

- **_buildSectionTitle(title: String):** Method to build a section title widget.

- **_buildActionButtons():** Method to build action buttons for profile management.

- **_showDeleteConfirmationDialog():** Method to show a confirmation dialog for deleting user information.

- **_showChangeInformationForm():** Method to show a form for changing user information.



