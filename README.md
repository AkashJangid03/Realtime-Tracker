# Realtime Tracker

**Realtime Tracker** is a web application that allows users to track their real-time location with high accuracy. Built with Node.js and leveraging Socket.io for real-time communication, this application provides a seamless experience for location sharing and tracking.

## Features

- **Real-Time Location Tracking**: View and share your location in real-time.
- **High Accuracy**: Utilizes the browser's geolocation capabilities for precise tracking.
- **Interactive Map**: Displays users on a dynamic map using Leaflet.js.
- **User Management**: Automatically handles user connections and disconnections.

## Technologies Used

- **Node.js**: Backend framework for server-side logic.
- **Express**: Simplifies routing and server configuration.
- **Socket.io**: Enables real-time, bidirectional communication between the client and server.
- **EJS**: Embedded JavaScript templating for rendering HTML pages.
- **Leaflet.js**: A modern, open-source JavaScript library for interactive maps.

## Usage

- Upon accessing the application, users will be prompted to allow location tracking.
- As users share their locations, markers will appear on the map, updating in real-time.
- If a user disconnects, their marker will be removed from the map.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Acknowledgments

- [Socket.io](https://socket.io/) for real-time communication capabilities.
- [Leaflet.js](https://leafletjs.com/) for creating interactive maps.
