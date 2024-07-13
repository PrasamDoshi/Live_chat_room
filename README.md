# Real-Time Chat Application

This is a simple real-time chat application built using Flask and Socket.IO. The application allows users to join chat rooms with unique IDs and communicate with each other in real-time. Messages are encrypted and decrypted using AES ECB mode without IV (Initialization Vector).

## Features

- Real-time messaging
- Unique room IDs for chat rooms
- Message encryption and decryption using AES ECB mode

## Technologies Used

- Flask
- Socket.IO
- HTML
- CSS
- JavaScript
- AES ECB mode for encryption

## Prerequisites

- Python
- Flask
- Flask-SocketIO
- PyCryptodome

## Installation

Clone the repository:

   ```bash
   git clone https://github.com/PrasamDoshi/Live_chat_room.git
   ```

## Running the Application

1. Start the Flask server:

   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://localhost:5000`.

3. Enter a unique room ID and start chatting!

## File Structure

- `app.py`: The main Flask application file.
- `static/`: Directory for static files (CSS).
- `templates/`: Directory for HTML templates.

## Usage

1. Enter a unique room ID on the homepage.
2. Click "Join Room" to enter the chat room.
3. Start sending and receiving messages in real-time.

## Encryption

Messages are encrypted and decrypted using AES ECB mode without an IV. Ensure that the key used for encryption and decryption is kept secure and is known to both the sender and receiver.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact

For any questions or issues, please contact [prasamdoshi1011@gmail.com].

---

Feel free to customize this `README.md` as needed for your specific project details.
