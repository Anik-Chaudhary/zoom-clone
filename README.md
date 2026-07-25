# Zoom Clone

A simple Zoom-like video conferencing application built with Node.js, Express, EJS, Socket.IO, and WebRTC concepts for real-time communication. It is designed as a learning project for understanding browser-based video meetings and real-time event handling.

## Features

- Real-time meeting room interface
- Video and audio communication support
- In-meeting chat
- Multiple participant support
- Browser-based access with responsive UI
- Real-time communication using sockets

## Tech Stack

- **Backend:** Node.js, Express
- **Templating Engine:** EJS
- **Realtime Communication:** Socket.IO
- **Frontend:** JavaScript, HTML, CSS
- **Package Management:** npm

## Project Structure

```bash
zoom-clone/
├── public/           # Static assets
├── views/            # EJS templates
├── server.js         # Main server entry point
├── package.json      # Dependencies and scripts
├── package-lock.json
├── plan.md
├── LICENSE
└── README.md
```

## Prerequisites

Before running the project, make sure you have:

- Node.js installed
- npm installed

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Anik-Chaudhary/zoom-clone.git
cd zoom-clone
```

2. Install dependencies:

```bash
npm install
```

## Run the Project

Start the server with:

```bash
npm start
```

If no start script is configured, run:

```bash
node server.js
```

Then open your browser and visit:

```bash
http://localhost:3030
```

## How It Works

- Users open the app in a browser.
- They join a meeting room.
- Socket-based events handle real-time interaction between participants.
- The UI is rendered using EJS templates and static frontend assets.

## Available Files

- `server.js` — Express server and application entry point
- `views/` — Server-rendered EJS pages
- `public/` — Client-side assets such as CSS, JavaScript, and media files
- `package.json` — Project metadata and dependencies

## Learning Purpose

This project is useful for learning:

- Real-time communication with Socket.IO
- Video meeting architecture basics
- Express server setup
- EJS templating
- Frontend and backend integration in Node.js apps

## Roadmap

Possible future improvements:

- Authentication
- Unique room generation
- Screen sharing
- Recording support
- Better meeting controls
- Deployment configuration

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes

```bash
git commit -m "Add your feature"
```

4. Push to your branch

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Developed by [Anik-Chaudhary](https://github.com/Anik-Chaudhary)

## Acknowledgments

This project was built for learning WebRTC and real-time communication by following a YouTube tutorial and making modifications during the implementation.
