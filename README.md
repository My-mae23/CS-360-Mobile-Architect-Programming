# CS-360-Mobile-Architect-Programming

# Event-Tracking App

## Overview

This mobile application is designed to help users track and manage events efficiently. It addresses the need for a centralized, user-friendly platform to organize event details, set reminders, and receive notifications.

## Requirements and Goals

-   Requirements: The app must allow users to create, update, delete, and view event details. It should also support user authentication and SMS notifications.
-   Goals: To provide a seamless event management experience, reduce missed events, and improve overall organization for users.

## User Interface and Features

### Screens:

1.  Login Screen: Allows existing users to log in and new users to create an account.
2.  Event List Screen: Displays a grid of all upcoming events.
3.  Event Detail Screen: Shows detailed information for a selected event, with options to edit or delete.
4.  Add Event Screen: Provides a form to create new events.
5.  Settings Screen: Manages user preferences and SMS permissions.

### UI Design Considerations:

-   User-Centered Design: The UI was designed with simplicity and ease of use in mind. Key actions are easily accessible, and the layout is intuitive.
-   Success: The design is successful because it prioritizes clear information presentation and reduces the number of steps required to perform common tasks.

## Coding Process

### Approach:

1.  Modular Design: Breaking down the app into smaller, manageable components.
2.  Version Control: Using Git for tracking changes and collaboration.
3.  Agile Development: Iterative development with frequent testing.

### Techniques:

-   Data Persistence: SQLite database for storing user and event data.
-   User Authentication: Securely storing and verifying user credentials.
-   SMS Notifications: Using Android’s SMS API with proper permission handling.

### Future Application:

These techniques can be applied to future projects by ensuring scalability, maintainability, and robustness of the codebase.

## Testing

### Process:

-   Unit Testing: Testing individual components in isolation.
-   UI Testing: Ensuring the UI behaves as expected under different scenarios.
-   Emulator Testing: Using Android Emulator to simulate various devices and conditions.

### Importance:

Testing is crucial to identify bugs, ensure functionality, and improve user experience. It revealed several edge cases and UI inconsistencies that were addressed before finalization.

## Innovation

### Challenges:

Implementing SMS notifications while respecting user privacy and permissions was a significant challenge.

### Solutions:

The app innovated by providing clear explanations of why SMS permissions are needed and ensuring full functionality even if the user denies permission.

## Successful Component

The database implementation was particularly successful. It efficiently stored and retrieved event data, supported CRUD operations (Create, Read, Update, Delete), and integrated seamlessly with the UI. This demonstrated strong knowledge of database management and Android development.
