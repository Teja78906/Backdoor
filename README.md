# Remote Shell Project

This Python project implements a basic remote shell using sockets for communication. It allows for remote command execution, file uploads, and downloads.

## Usage

1. **Server Setup:**

   - Run the `client.py` script on the machine you want to control remotely.

     ```bash
     python client.py
     ```

   - The server will listen for incoming connections on IP address `192.168.1.12` and port `5555`.

2. **Client Setup:**

   - Run the `client.py` script on the target machine.

   - The client will connect to the server, and you will get a remote shell prompt.

3. **Commands:**

   - Enter commands on the shell, and they will be executed on the target machine.

   - Supported commands:
     - `quit`: Terminate the connection.
     - `clear`: Clear the screen.
     - `cd <directory>`: Change the current working directory on the target machine.
     - `download <file>`: Download a file from the target machine.
     - `upload <file>`: Upload a file to the target machine.

## Files

- `server.py`: Contains the server-side code.
- `client.py`: Contains the client-side code.

## Requirements

This project relies on the following Python modules, which are part of the standard library:

- `socket`
- `json`
- `os`

## Disclaimer

This project is intended for educational purposes only. Use it responsibly and ensure that you have appropriate authorization before attempting to control remote machines.


