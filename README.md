# ChatSphere

## Overview
ChatSphere is a real-time chat application built using Flask, Flask-SocketIO, and JavaScript. It allows users to join, send messages, and update their usernames dynamically.

## Features
- Real-time messaging using WebSockets
- Automatic username assignment
- Ability to update usernames
- Dark and Light theme toggle
- User avatars based on randomly assigned gender

## Installation
### 1. Clone the repository
```bash
git clone https://github.com/Vegeta909/ChatSphere.git
cd ChatSphere
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows
```

### 3. Install dependencies
```bash
pip install Flask Flask-SocketIO eventlet
```

### 4. Run the application
```bash
python app.py
```

### 5. Open the app in your browser
Go to `http://127.0.0.1:5000` in your browser to start chatting!

## Project Structure
```
ChatSphere/
│── static/
│   ├── css/
│   │   └── styles.css
│   ├── script/
│   │   └── script.js
│── templates/
│   └── index.html
│── app.py
│── README.md
```

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask, Flask-SocketIO
- **WebSockets**: Real-time communication with Socket.IO

## License
This project is licensed under the MIT License.

---
Made by [Vegeta909](https://github.com/Vegeta909)
