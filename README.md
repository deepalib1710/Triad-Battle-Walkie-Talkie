# Triad Battle Walkie-Talkie

A real-time web-based walkie-talkie application that enables voice communication between multiple users across different frequency channels using WebRTC technology.

## Features

**Multi-Channel Communication**
- Three distinct frequency channels (Channel 1, 2, 3)
- Switch between channels in real-time
- Independent audio streams per channel

**Push-to-Talk (PTT) Control**
- Hold-to-talk functionality for transmission control
- Disabled by default for privacy
- Interactive visual feedback during transmission

**Real-Time Audio Visualization**
- Live frequency spectrum display
- Visual feedback for both local and remote audio
- Dynamic color-coded audio levels

**WebRTC Peer-to-Peer Communication**
- Direct peer connections with ICE candidates
- Signaling server for connection negotiation
- Support for multiple simultaneous connections per channel

**User-Friendly Interface**
- Bootstrap 5 responsive design
- Connection status indicators
- Microphone and remote device status displays
- Latency monitoring

## Technologies Used

- **Frontend:** HTML5, JavaScript, Bootstrap 5
- **Backend:** Node.js, Express.js
- **Real-Time Communication:** WebRTC, Socket.io
- **Audio Processing:** Web Audio API

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)
- A modern web browser with WebRTC support

### Installation

1. Clone the repository:
```bash
git clone https://github.com/deepalib1710/Triad-Battle-Walkie-Talkie.git
cd Triad-Battle-Walkie-Talkie
