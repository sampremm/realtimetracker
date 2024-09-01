

# Real-Time Location-Sharing Web Application

## Overview

This project is a real-time location-sharing web application that allows users to share their geographical location with others in real-time. Built with **Express.js**, **Socket.IO**, and **Leaflet.js**, the application provides an interactive map experience for users to see each other's locations and track movements in real-time.

## Features

- **Real-Time Location Tracking**: Uses Socket.IO to establish WebSocket connections for live location updates.
- **Interactive Map**: Integrates Leaflet.js to display user locations dynamically on a map.
- **User Management**: Handles user connections and disconnections, broadcasting updates to all connected clients.
- **High-Accuracy Geolocation**: Utilizes navigator.geolocation with high accuracy settings for precise location tracking.

## Technologies Used

- **Express.js**: A minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
- **Socket.IO**: A library that enables real-time, bidirectional, and event-based communication between web clients and servers.
- **Leaflet.js**: A leading open-source JavaScript library for interactive maps.
- **EJS**: A templating engine that helps render dynamic HTML content on the server side.

## Installation

1. Clone the repository:
  

2. Navigate to the project directory:
   

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:9000` to view the application.

## Usage

- **Share Location**: Users can share their real-time location, which is then broadcasted to all connected clients.
- **View Locations**: The application displays the locations of all users on an interactive map.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes. For more information, see the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Leaflet.js**: For providing a powerful mapping library.
- **Socket.IO**: For enabling real-time communication.
- **Express.js**: For simplifying server-side development.

