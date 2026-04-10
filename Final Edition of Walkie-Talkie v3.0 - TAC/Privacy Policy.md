1. Data Collection
The TAC/COM v12.3 application does not collect, store, or share any personal identifiable information (PII). All communication data is transmitted directly between peers.

2. Microphone Usage
The application requires access to your device's microphone to facilitate audio communication. Audio is processed locally for DSP filtering and then encrypted before transmission. No audio data is recorded or stored on any server.

3. Peer-to-Peer Transmission
Communication occurs over a Peer-to-Peer network. While the application uses a public MQTT broker for the initial handshake, the actual data payloads are:

Encrypted: Using AES-GCM 256-bit encryption.

Ephemeral: Data exists only during the active session and is not logged.

4. Third-Party Services
This project utilizes the following third-party libraries:

MQTT (EMQX Broker): For signaling and handshake logic.

PeerJS: For direct P2P connection handling.
Please refer to their respective privacy policies regarding metadata handling during connection handshakes.

5. Local Storage
The application may use browser sessionStorage or local variables to maintain your frequency and key settings during a single session. This data is wiped upon closing the browser tab.
