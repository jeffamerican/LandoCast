**USAGE.md**

## Usage Guide for Landocast

# Starting the Application

1. Launch OBS and set up your screen capture.
2. Run the WebRTC signaling server:
  npm start

3. Connect via Browser:
  Open the web application in your browser.
  Generate a connection link and share it with the remote viewer.
  Start streaming your AVID session.

# Troubleshooting

Connection Issues: If the connection fails, check your network settings and ensure that STUN/TURN servers are correctly configured.

Audio Sync Problems: Verify that your audio input settings in OBS are correctly configured and that there is minimal latency in your setup.

# Advanced Configuration

Custom TURN Server: Edit the WebRTC configuration file to use a custom TURN server if required.

Network Bandwidth: Adjust bitrate settings in OBS to optimize performance based on available bandwidth.
