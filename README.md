# 🎨 Real-Time Collaborative Whiteboard

A modern real-time collaborative whiteboard that enables multiple users to draw, sketch, and brainstorm together seamlessly. Built using modern web technologies with WebSocket-based communication for instant synchronization across connected clients.

## 🚀 Features

- ✏️ Real-time collaborative drawing
- 👥 Multiple users can draw simultaneously
- ⚡ Instant synchronization using WebSockets
- 🎨 Freehand drawing
- 🧹 Clear canvas functionality
- 📱 Responsive and user-friendly interface
- 🔄 Live updates without page refresh

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5 Canvas
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js
- Socket.IO

---

## 📂 Project Structure

```
real-time-collaborative-white-board/
│
├── client/          # React Frontend
├── server/          # Node.js Backend
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ipragyabharti/real-time-collaborative-white-board.git
```

### 2. Navigate to the project

```bash
cd real-time-collaborative-white-board
```

### 3. Install dependencies

For the frontend:

```bash
cd client
npm install
```

For the backend:

```bash
cd ../server
npm install
```

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm start
```

The application will typically run on:

- Frontend: `http://localhost:3000`
- Backend: `http://localhost:5000`

---

## 💡 How It Works

1. Users connect to the same whiteboard.
2. Drawing events are sent to the server using Socket.IO.
3. The server broadcasts these events to all connected users.
4. Every connected client updates its canvas instantly, enabling real-time collaboration.

---

## 📸 Screenshots

> Add screenshots of your application here.

Example:

```
screenshots/
    home.png
    drawing.png
```

---

## 🌟 Future Improvements

- User authentication
- Room-based collaboration
- Undo/Redo functionality
- Shape tools
- Color palette
- Stroke size adjustment
- Image upload
- Save whiteboard as PNG/PDF
- Persistent whiteboard storage

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Pragya Bharti**

GitHub: https://github.com/ipragyabharti
