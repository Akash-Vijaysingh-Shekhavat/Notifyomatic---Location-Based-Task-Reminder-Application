# Notifyomatic - Location Based Task Reminder

## Introduction

Notifyomatic is a system that notifies users of tasks based on their location. Unlike traditional time-based reminders, this app triggers notifications when users are physically present in a designated area. Designed for Android smartphones and tablets, Notifyomatic ensures tasks are completed at the right place and time.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Location-Based Reminders:** Set reminders that trigger when you are near a specific location.
- **Time-Based Reminders:** Option to set reminders for a specific time.
- **Traffic Information:** Provides traffic updates for your destination.
- **Data Privacy:** Ensures privacy by encrypting data and not constantly tracking user location.
- **User-Friendly Interface:** Simple and intuitive design for easy use.

## Screenshots

### Signup Screen
![Signup Screen](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/5851a850-d68e-4d6d-96fb-0d62aa88e0d6)

### Login Screen
![Login Screen](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/18ae7e7b-e9fa-4be8-9cbe-a8c9ef1512e2)

### Home Page
![Home Page](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/ec06d489-8889-4540-bdc3-c7c7d8a6923e)

### Maps
![Maps](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/2d88cee0-28fc-46fa-bbee-54979eba6fa3)

### To-Do List
![To-Do List](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/10a4e82d-a741-416d-9838-6a4240fe55e6)

### Add a Note
![Add a Note](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/7068e576-a54f-47f8-a895-a114b208a5cd)

### Geofence
![Geofence](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/8dd337e3-6502-40f4-8c48-1516f12fb8aa)

### Notification
![Notification](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/2ee1236b-369a-4aff-a1d3-411da60f0ca2)

### Feedback
![Feedback](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/aced4022-0384-4e15-a947-b03317357f5c)

### Support
![Support](https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application/assets/90681684/c1bdc8ef-1afa-482e-86ec-1079b2becd2b)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akash-Vijaysingh-Shekhavat/Notifyomatic---Location-Based-Task-Reminder-Application.git
2. Open the project in Android Studio.
3. Build the project to download necessary dependencies.
4. Run the application on an emulator or physical device.

## Usage

1. **Sign Up / Log In:** Create a new account or log in with existing credentials.
2. **Set Location-Based Reminder:**
   - Select a desirable location on the map.
   - Set the reminder details.
3. **Geofence:** Define geofence areas to receive notifications when entering, dwelling, or exiting the area.
4. **To-Do List:** Manage your tasks with title, location, date, and description.
5. **Notifications:** Receive notifications when you approach your designated task location.

## Methodology

### Algorithm for Location-Based Task Reminder:

1. Create a developer account and generate API keys for Google Maps.
2. Grant necessary permissions (internet, fine location, coarse location, background location).
3. Enable location services if not already enabled.
4. Display user's live location on the map.
5. Allow users to set geofence areas by long-pressing on the map.
6. Trigger notifications based on user's presence within the geofence.

### Haversine Formula:
Used to compute the distance between the set location and user's location.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


