# CAR-MULTIPLAYER
<img width="1536" height="1024" alt="background image" src="https://github.com/user-attachments/assets/28cf0a0f-a7fe-4d87-a6f9-0b745eb876dd" />


# 🚗 Car Multiplayer

A real-time multiplayer top-down car racing game controlled with **W A S D** keys.

---

## 🎮 Gameplay

Race against other players in real time. Each player controls their own car using the keyboard. Dodge others, stay on track, and reach the finish line first.

### Controls

| Key | Action |
|-----|--------|
| `W` | Accelerate forward |
| `S` | Brake / Reverse |
| `A` | Steer left |
| `D` | Steer right |

---

## 🕹️ Features

- Real-time multiplayer via WebSockets
- Top-down 2D car physics
- Player name tags and car colors
- Collision detection between cars
- Live leaderboard / lap counter
- Responsive canvas rendering

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- npm or yarn

### Installation

```bash
git clone https://github.com/your-username/car-multiplayer.git
cd car-multiplayer
npm install
```

### Run the Server

```bash
npm start
```

Then open your browser at:

```
http://localhost:3000
```

Share that URL with friends on the same network (or deploy it) to play together.

---

## 🗂️ Project Structure

```
car-multiplayer/
├── public/
│   ├── index.html       # Game canvas and UI
│   ├── game.js          # Client-side game loop & rendering
│   └── style.css        # Styles
├── server.js            # Node.js + Socket.io server
├── package.json
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5 Canvas, Vanilla JS |
| Backend | Node.js, Express |
| Networking | Socket.io (WebSockets) |

---

## 🌐 Multiplayer Architecture

1. Each player connects to the server via WebSocket.
2. The client sends keyboard input (`W`, `A`, `S`, `D`) on every frame.
3. The server processes movement, resolves collisions, and broadcasts updated positions to all players.
4. Each client renders all cars based on the state received from the server.

---

## 📦 Scripts

```bash
npm start        # Start the game server
npm run dev      # Start with hot-reload (nodemon)
npm test         # Run tests
```

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

MIT © EBINBIJU138


<img width="107" height="50" alt="resume" src="https://github.com/user-attachments/assets/c68a9824-bb2f-4511-a29d-55fe557fb3ee" />
<img width="65" height="57" alt="resume icon" src="https://github.com/user-attachments/assets/dc5e2874-9498-424f-a235-efe51d2bafd8" />
<img width="711" height="219" alt="quit" src="https://github.com/user-attachments/assets/dd98695a-8597-46ef-a3c7-432978869f51" />
<img width="711" height="219" alt="play" src="https://github.com/user-attachments/assets/9b5d33b0-b573-4b88-8203-c54e39721ed2" />
<img width="112" height="116" alt="PAUSE" src="https://github.com/user-attachments/assets/bae9f7bc-73d1-4478-960a-20d12d68386c" />
<img width="60" height="56" alt="pause icon" src="https://github.com/user-attachments/assets/bd75da72-7313-4f13-99c3-742ccce20538" />
<img width="884" height="248" alt="HOST" src="https://github.com/user-attachments/assets/afcdbd12-33fb-4c25-86ec-da558e2f7c96" />

<img width="1073" height="294" alt="CLIENT" src="https://github.com/user-attachments/assets/cbe39b9b-64e3-4057-8586-672489c19240" />



<img width="1091" height="299" alt="SERVER" src="https://github.com/user-attachments/assets/a7fc551a-05e7-4f38-9a90-83a2ed4b4ca5" /><img width="711" height="219" alt="settings" src="https://github.com/user-attachments/assets/3c0516ed-0d20-4b70-babe-f0e1f9de6459" />
