.. _about_us_page:

About Us Page
=============

The About Us Page provides information about the team behind the WasteAway application, their roles, and contact details.

Functionality
-------------

The About Us Page includes the following functionality:

- **Email Launch:** The `_launchEmail()` method is used to launch the default email app when the "Contact by email" option is tapped. It is implemented for multiple team members, each with their email address.
- **Page Structure:** Utilizes a `Scaffold` widget with an `AppBar` for navigation and a `SingleChildScrollView` to enable scrolling through the content.
- **Team Information:** Displays information about each team member, including their name, role, brief description, and an option to contact them via email.

Implementation Details
----------------------

The About Us Page is implemented in the `AboutUsPage` class, which extends `StatelessWidget`. Key implementation details include:

- **AppBar:** Displays the title "About Us" with a green background and a custom font size.
- **Background:** Sets the background color of the page to a light green shade.
- **Page Content:** Organizes team member information in a column within a container. Each team member's details are presented in a separate container with an image, name, role, description, and an option to contact them via email.
- **Email Launch:** Defines methods `_launchEmail()`, `_launchEmail2()`, `_launchEmail3()`, `_launchEmail4()`, `_launchEmail5()`, and `_launchEmail6()` to handle email launches for each team member.
