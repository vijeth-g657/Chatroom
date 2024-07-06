
# Chatroom in C

This is a simple chat application for Linux-based systems built in C using web sockets. It allows multiple clients to communicate with each other within a chatroom environment.

## Features

- Multiple clients can join a chatroom and communicate with each other in real-time.
- Each client is required to enter their name, which serves as their unique user ID.
- Messages are stored in a file, allowing clients to retrieve unread messages upon joining the chatroom.
- The application handles Ctrl+C signals gracefully to ensure proper termination.

# Run the Program
Run the Makefile using the command 

$ make Makefile compile

./server.c 4444

./client.c 4444


