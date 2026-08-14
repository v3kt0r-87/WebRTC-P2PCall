# P2P Voice Call (WebRTC & PeerJS)

This is a lightweight browser-based peer-to-peer voice calling application built using WebRTC and PeerJS, designed for zero-latency communication during gaming sessions or when standard VOIP apps fail.

[View Live App](https://v3kt0r-87.github.io/WebRTC-P2PCall/)

## Features

- **P2P Audio Communication:** Direct WebRTC browser-to-browser voice streaming with no intermediate audio servers.
- **Hardware Audio Processing:** Real-time toggles for Noise Suppression and Echo Cancellation via WebRTC track constraints.
- **Microphone Mute & Hotkey:** Quick mic mute toggle with keyboard shortcut support (<kbd>M</kbd> to mute, <kbd>Esc</kbd> to end/decline).
- **Call Management:** Incoming call accept/decline prompt with zero-latency synthesized Web Audio ringtones and connect chimes.
- **Direct Invite Links:** Share one-click join links (`?call=USERNAME`) for quick party setup.
- **Audio Dynamic Compression & Gain:** Gain slider (0x to 3.0x) with dynamics compression to prevent clipping.
- **Live Telemetry & Diagnostics:** Real-time stats for average RTT latency, jitter, packet loss, connection integrity, network routing type, and IP resolution.
- **Audio Visualizer:** Dynamic HTML5 canvas waveform visualizer.
- **Session Persistence:** Remembers your chosen username via local storage.

## Keyboard Shortcuts

| Key | Action |
| --- | --- |
| <kbd>Enter</kbd> | Submit username / Initiate call |
| <kbd>M</kbd> | Toggle Microphone Mute / Live |
| <kbd>Esc</kbd> | Cancel outgoing call / Decline incoming / Terminate active call |

## Technologies Used

- **WebRTC** (Real-Time Communications)
- **PeerJS** (P2P Signaling)
- **Web Audio API** (Audio graph processing, compression, visualizer, sound cues)
- **HTML5 & Vanilla CSS3** (Matrix digital rain canvas, cyber glassmorphism terminal)
- **Vanilla JavaScript** (Zero framework bloat)

## License

This project is licensed under the GNU GPL v3 License.
