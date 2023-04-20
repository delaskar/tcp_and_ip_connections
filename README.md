# Chat Server and Client
This is a simple chat application consisting of a server and client written in Python. The server and client communicate with each other using sockets and the 
***TCP/IP*** protocol. The socket module comes preinstalled with Python.

## Prerequisites
Before running this application, you need to have Python installed on your computer. If you don't have Python installed, you can download it from the official website. The version of Python that I use for this program is **Python3**. => https://www.python.org/downloads/. 

## Usage

### Server
Open a terminal window and navigate to the directory where the ***chat_server.py*** file is saved.
Run the server by entering the following command: 
`python chat_server.py`
The server will start running and wait for incoming connections.

### Client
Open a new terminal window and navigate to the directory where the ***chat_client.py*** file is saved.
Run the client by entering the following command: 
`python chat_client.py`
The client will connect to the server and wait for incoming messages.
Start sending and receiving messages by typing them in the terminal window.
Note: To end the chat, type "quit" in the terminal window.

You need to open two terminal windows, one for the server and another one for the client. You can resize the terminal windows so that you can see both the server and the client terminals at the same time.