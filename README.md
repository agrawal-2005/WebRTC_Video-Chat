# Video Chat Application

This project is a simple video chat application built using React, Node.js, and Socket.IO for real-time communication.

## Features

- Video calling between two peers
- Real-time chat
- Responsive UI using Material-UI

## Technologies Used

- **Frontend**: React, Material-UI
- **Backend**: Node.js, Express.js, Socket.IO
- **Peer-to-Peer Communication**: simple-peer
- **Styling**: CSS

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Node.js installed on your local machine
- npm (Node Package Manager) or yarn installed

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/video-chat-app.git
   ```

2. Navigate into the project directory:

   ```bash
   cd video-chat-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

### Setting up the Backend Server

1. Navigate to the server directory:

   ```bash
   cd server
   ```

2. Install server dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

   The server will run at `http://localhost:5001`.

### Starting the Frontend

1. Navigate back to the root directory of the project:

   ```bash
   cd ..
   ```

2. Start the React development server:

   ```bash
   npm start
   ```

   This will open the application in your default web browser at `http://localhost:3000`.

## Usage

1. Open two instances of the application in separate browser tabs or on different devices.
2. Enter your name and copy your ID.
3. Enter the ID of the person you want to call.
4. Click the "Call" button.
5. Once the call is accepted, you can see and hear each other via video and audio.

## Contributing

Contributions are welcome! Fork the project and submit a pull request with your proposed changes.

## Acknowledgments

- This project was inspired by the need for simple and effective video conferencing solutions.
- Special thanks to the developers of React, Node.js, and Socket.IO for their amazing tools and libraries.