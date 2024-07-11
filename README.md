Real-Time Chat Room Application

Overview
This project is a real-time chat room application built using Flask and Socket.IO. Users can create or join chat rooms with a unique room ID to interact with each other in real time. The chat messages are encrypted using AES ECB (Electronic Codebook) mode without an IV (Initialization Vector).

Features
Real-time communication using Flask and Socket.IO.
Unique room IDs for each chat room.
AES ECB encryption for secure communication.
Simple and user-friendly interface.

Prerequisites
Before you begin, ensure you have the following installed:

Python 3.x
Flask
Flask-SocketIO
PyCryptodome (for AES encryption)

Installation
Clone the repository:

sh
Copy code
git clone https://github.com/yourusername/Live_chat_room.git
cd chat-room
Create and activate a virtual environment:

sh
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Usage
Run the application:

sh
Copy code
python app.py
Access the application:
Open your web browser and navigate to http://127.0.0.1:5000.

Create or join a chat room:

Enter a unique room ID to create or join a chat room.
Start chatting with other users in the room.
