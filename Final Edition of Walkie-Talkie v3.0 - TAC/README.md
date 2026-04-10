# TAC/COM v12.3 | Bi-Directional Field Radio

An interactive, peer-to-peer (P2P) tactical communication dashboard designed for low-latency audio and text relays. Built for web developers and hobbyists interested in signal intelligence simulations.

## 📡 Features
- **Bi-Directional Rotary Tuning**: Change frequencies by clicking the left or right side of the mechanical nozzle.
- **P2P Audio Relay**: Secure, real-time voice communication using PeerJS and MQTT.
- **AES-GCM Encryption**: 256-bit encryption for all transmitted data packets.
- **Tactile UI**: Features an oscilloscope, signal RSSI bars, and a "Retro-OS" aesthetic.
- **ANC (Active Noise Cancellation)**: Integrated DSP filter to reduce environmental static.

## 🚀 Deployment
1. Copy the `index.html` (Master File) to your repository.
2. Deploy via **GitHub Pages** or any static hosting service.
3. Open the URL in a browser and grant **Microphone Permissions**.

## 🛠️ Controls
- **Master On/Off**: Powers the hardware and initializes the visual scope.
- **Nozzle (Top-Right)**: 
    - Click **Left**: Decrease frequency.
    - Click **Right**: Increase frequency.
- **PTT (Push-To-Talk)**: Hold to transmit audio; release to listen.
- **ANC**: Toggle the noise suppression filter for clearer audio.

## 🔒 Security
Connections are established via an encrypted handshake. Ensure both parties use the same **Channel** and **TAC-KEY** to communicate.
