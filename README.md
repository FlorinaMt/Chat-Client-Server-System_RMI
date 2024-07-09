## About project

Simple chat client-server system using RMI. Create account, send text messages to other users or request information from server using commands: "/list", "/number", "/last". The whole conversation is logged in .txt files, one file for each day.

### Requirements

The client must be able to 1) send messages, 2) receive messages broadcasted to all clients and 3) request information from the server (not broadcasted to other clients, e.g. number of connected chatters, list of connected chatters or similar).

The application must:

- use RMI connecting client and server

- use MVVM with at least two windows.

- use the Observer design pattern.

- use either Singleton or Multiton as a log to the server console and to file(s). It should always be possible to find all the communication for an entire day –text, ip address, date and time.

### Class Diagram

![image](https://github.com/FlorinaMt/Chat-Client-Server_RMI/assets/151634373/f95f2cf0-f08f-450b-8f54-ea5d6e2208ac)
