# Landocast

## Overview
Landocast is a P2P-based software application designed for low-latency collaboration during offline video editing, specifically when using AVID. The primary focus is on achieving the lowest possible latency and ensuring audio synchronization between the editor and one or two remote viewers. Video quality is secondary, as the tool is intended for real-time feedback rather than final delivery.

## Features
- Ultra-low latency video streaming using WebRTC.
- Synchronized audio streaming.
- Simple user interface for easy connection management.
- Support for one or two remote viewers.
- Integration with OBS for screen capture.

## Getting Started
### Prerequisites
- **Node.js** for running the WebRTC signaling server.
- **OBS Studio** for screen capture.
- Basic understanding of WebRTC and AVID.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/jeffamerican/landocast.git

2. Install Dependencies:
  cd landocast
  npm install

3. Start the signaling server:
   npm start

###  Usage
Start OBS and configure it to capture your AVID preview monitor.
Run the WebRTC connection from your browser or dedicated application.
Share the connection link with your remote viewer.
Begin editing and receive real-time feedback with minimal delay.


### Contributing

Contributions are welcome! Please see CONTRIBUTING.md for details on our code style and pull request process.

### License

This project is licensed under the MIT License - see the LICENSE.md file for details.

### Acknowledgments

Thanks to the WebRTC community for providing resources and inspiration.
