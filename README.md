# ♟️ Real-Time Multiplayer Chess Game  
### Built with **Node.js**, **Express.js**, **Socket.IO**, and **Chess.js**

## 🎥 Demo Video

[▶️ **Watch Game Demo**](/assests/chess.mp4)

## 🖼️ Chessboard Preview

### White Player View  
![Chessboard White](/assests/chess1.png)

### Black Player View  
![Chessboard Black](/assests/chess2.png)

---

## 🚀 Features

- **Real-time gameplay** using Socket.IO  
- **Auto player assignment** (White / Black / Spectator)  
- **Drag & drop chess pieces**  
- **Board auto rotation** for black  
- **Move validation with Chess.js**  
- **Fully synced game state across all clients**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Node.js | Backend |
| Express.js | Server |
| Socket.IO | Real-time events |
| Chess.js | Logic & validation |
| HTML / CSS | UI |
| TailwindCSS | Styling |

---

## 📁 Project Structure

```

Chess-Game/
│
├── public/
│   ├── index.html
│   ├── css/style.css
│   └── js/chessgame.js
│
├── server.js
└── package.json

````

---

## ⚙️ Setup & Installation

### 1. Clone Repository
```bash
git clone https://github.com/your-username/Chess-Game.git
cd Chess-Game
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Server

```bash
node server.js
```

### 4. Open in Browser

```
http://localhost:3000
```

---

## 🔌 Socket.IO Events

### **Client → Server**

* `move` – sends move object `{from, to}`

### **Server → Client**

* `playerRole`
* `spectatorRole`
* `boardState`
* `move`

---

## ♟️ How the Game Works

* Board is drawn using **CSS Grid** (8×8)
* Drag & drop pieces with HTML drag events
* Server validates moves using **Chess.js**
* Black player sees a **rotated board**
* Moves broadcast to all clients

---

## 🔮 Future Improvements

* Move history (PGN)
* Game timer
* Matchmaking lobby
* Authentication
* Sounds & animations

---

## 🤝 Contributing

Feel free to submit pull requests or open issues.

---

## 📜 License

MIT License

```

