# TCP Chat Application

**This repository contains Python scripts for a basic TCP chat application comprising a client (`client.py`) and a server (`server.py`).**

## Client Script (`client.py`)

**The `client.py` script functions as a TCP client for the chat application.**

### Prerequisites

- Python 3.x

### Usage

1. Run the script: `python client.py`
2. Choose a nickname for yourself.
3. If your nickname is 'admin', you will be prompted to enter a password.
4. Start sending messages to the chat server.

### Commands

- **`/kick [nickname]`:** Admins can use this command to kick a user from the chat.
- **`/ban [nickname]`:** Admins can use this command to ban a user from the chat.

## Server Script (`server.py`)

**The `server.py` script functions as a TCP server for the chat application.**

### Prerequisites

- Python 3.x

### Usage

1. Run the script: `python server.py`
2. The server will start listening for incoming connections.
3. Clients can connect to the server using a chosen nickname.

### Commands

- **`/kick [nickname]`:** Admins can use this command to kick a user from the chat.
- **`/ban [nickname]`:** Admins can use this command to ban a user from the chat.

## Important Notes

- The `client.py` script enables clients to connect to the chat server and engage in conversations.
- The `server.py` script serves as the chat server, handling incoming connections, messages, and admin commands.
- **Admins possess special privileges**, including the authority to kick or ban users from the chat.
- Banned users are recorded in the `bans.txt` file.
- **This is a rudimentary implementation and lacks security features. It is recommended for educational purposes and local usage only.**
