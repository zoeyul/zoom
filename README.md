# zoom

Zoom Clone using Nodejs, WebRTC, and Websockets

### 🛠 Tech Stack & Tools
- Styling: Used MVP.css for automatic, no-class CSS styling.
- Templating Engine: Pug for streamlined HTML structure.
- Server: Built with Express.
- Development Tools: * Nodemon to automatically restart the server on file changes.
- Babel to compile modern JavaScript into standard Node.js code.
- babel-node used for running the project in the development environment.

## ✨ Features
### 💬 Real-time Messaging
- WebSocket Integration: Implemented a basic chat system using native WebSockets (feature/websocket).
- Socket.io Chat Rooms (feature/socketio):
  - Create and join specific chat rooms.
  - Real-time notifications for user Join/Exit events.
  - Nickname synchronization and message broadcasts within rooms.
  - Global alerts for the creation or deletion of chat rooms.
  - Live user count tracking per room.
  - Integrated Socket.io Admin Panel for server-side monitoring.

### 📹 Video Call & WebRTC
- Media Controls: Toggle audio (Mute/Unmute) and video (On/Off).
- Device Management: Dynamic camera switching via a localized device list.
- P2P Video Streaming: * Side-by-side view of local and remote video streams on a single page.
  - Synchronized camera updates across all connected peers.
- Connectivity:
  - Used localtunnel for mobile device testing and external access.
  - Integrated STUN servers to enable connections across different networks (NAT traversal).
  - Implemented WebRTC Data Channels for low-latency data exchange (feature/data-channel).

### 📂 Project Structure
- Backend: Server logic is handled in src/server.js.
- Frontend: All client-side assets and logic are managed within the src/public directory.
