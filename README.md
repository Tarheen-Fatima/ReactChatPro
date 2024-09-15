# ReactChatPro

A modern real-time chat application built on [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/), and [Socket.io](https://socket.io/). ReactChatPro delivers seamless, responsive, and engaging chat experiences with WhatsApp-inspired features.

Key Features
- Real-Time Messaging: Users can chat instantly with real-time updates using WebSockets (Socket.IO).
- Smooth Background Animations: Subtle, smooth background transitions provide a dynamic and engaging visual experience.
- WhatsApp-Inspired UI: A user interface that mimics the familiar WhatsApp design, making it easy to use.
- Message Timestamps: Display the time when each message is sent, ensuring clarity in conversation.

# Pre-requisites

To run this project locally for development or testing, ensure you have the following installed:
- Node.js (Tested with version 10.16.3)
- NPM (Comes with Node.js)

You can download Node.js from [https://nodejs.org/en/download](https://nodejs.org/en/download/).

Alternatively, you can use Node Version Manager (nvm) to manage multiple Node.js versions on your machine. Install it from [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm).

# Installation

Clone the repository from GitHub and install the required Node modules:

```bash
git clone https://github.com/yourusername/ReactChatPro.git
cd ReactChatPro
npm install
```

This will install all necessary dependencies.

# Running the App in Development Mode

To run the app in development mode, use the following command:

```bash
npm run dev
```

This will start the server at port 3000. Open your browser and navigate to [http://localhost:3000/](http://localhost:3000/) to view the app. The development server is powered by `nodemon`, so any changes you make to the code will trigger an automatic reload.

# Technology Stack

- Frontend: HTML5, CSS3
- Backend: Node.js, Express.js
- Real-time Communication: Socket.IO
- Development Tool: Nodemon

# Contributing

Contributions are welcome! To contribute:
1. Fork the project.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.
