.. _home_page:


Home Page
=========

Usage
-----

The home page serves as the main interface of the application, providing users with access to various features and functionalities. Here's an overview of what the software does:

- **Navigation:** Users can navigate through different sections of the application using the app drawer or by watching the introductory video provided on the home page.
- **Content Display:** It displays the application logo, a welcome message, and options to watch an introductory video or access other features.
- **Notification Handling:** The home page notifies users about expired ingredients and system inefficiency warnings.

Maintenance
-----------

The maintenance section describes how the software achieves its functionality and how developers can maintain and extend it:

- **Code Structure:**

  - `home_page.dart`: This file contains the implementation of the home page UI and logic. It includes methods to sign out users and notify about expired ingredients.

  - `food_notifications/notifications.dart`: This file manages the display and handling of the apps notifications. It includes functionality for retrieving and presenting notification data to users.

  - `components/app_draw.dart`: Implements the application drawer component, providing navigation options and sign-out functionality.

  - `components/video_player.dart`:  Implements the video player widget used to play the introductory video.

- **Functionality:**

  - **Navigation:** The app drawer allows users to navigate to different sections of the application, while the introductory video provides an overview of the application's features.

  - **Notification Handling:** The `NotificationManager` class handles notification logic, including removing expired ingredients and warning about system inefficiencies.

  - **Content Display:** The home page displays the application logo, welcome message, and options to watch the introductory video or take further actions.

 
