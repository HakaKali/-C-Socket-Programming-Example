# C Socket Programming Example

This is a simple example of socket programming in C, demonstrating how to create a basic server and client for communication.


## Description

This project provides a simple implementation of a server and client in C for socket communication. The server listens for incoming connections, and the client connects to the server. Once connected, the client can send a message to the server, and the server will respond with a confirmation message.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- GCC (GNU Compiler Collection)

### Installation

Follow these steps to compile and run the server and client:

1. Clone this repository:

   ```bash
   git clone https://github.com/HakaKali/-C-Socket-Programming-Example.git

2. Navigate to the project directory:

   ```bash
    cd -C-Socket-Programming-Example

3. Compile the server:
   ```bash
   gcc -o server server.c

4. Compile the client:
   ```bash
   gcc -o client client.c

### Usage

1. Start the server:

   ```bash

   ./server 1234

Replace 1234 with the desired port number.

2. Start the client:

   ```bash

   ./client 127.0.0.1 1234

Replace 127.0.0.1 with the server's IP address and 1234 with the server's port number.

Enter a message in the client terminal. The message will be sent to the server.

The server will receive the message, process it, and send a confirmation back to the client.

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
