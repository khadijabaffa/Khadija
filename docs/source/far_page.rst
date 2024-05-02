Frequently Asked Questions (FAQ) Page
======================================

The FAQ Page provides answers to commonly asked questions about the Recipe Generator app.

Functionality
-------------

The FAQ Page includes the following functionality:

- **Search:** The search box located at the top of the page allows users to search for specific questions.
- **Filtering:** As users type their query into the search field, the list of questions is dynamically filtered to show relevant results.
- **Expansion Tiles:** Each question is displayed as an expansion tile, allowing users to expand to view the answer.
- **Styling:** Questions and answers are styled for readability, with customizable colors for the tile background, title, and content.

Implementation Details
----------------------

The FAQ Page is implemented in the `FAQ_page` class, which extends `StatefulWidget`. Key implementation details include:

- **AppBar:** Displays the title "Frequently Asked Questions" with a green background.
- **Search Bar:** A search bar is provided at the top of the page, allowing users to search for specific questions.
- **Expansion Tiles:** Each question is represented as an `ExpansionTile`, with the question as the title and the answer as the expanded content.
- **Filtering Logic:** As users type in the search bar, the list of questions is filtered based on the entered query, providing real-time search results.
- **Clear Button:** A "Clear" button allows users to reset the search field and view all questions.
- **List View:** The list of questions is displayed within a `ListView.builder`, allowing for efficient scrolling and dynamic loading of questions.

