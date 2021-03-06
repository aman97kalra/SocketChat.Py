# SocketChat.Py
This is a simple chat app using Sockets and Tkinter(GUI) in Python. It uses TCP over UDP for obvious reasons.
The user is presented with a chat room interface. Multiple users can send messages simultaneously.
Make sure Tkinter is installed in your Python env.

### There are four scripts:
1) Server1.py (for Group Chat)
2) Server2.py (for Image Transfer)
3) Server3.py (for Video Chat)
4) Client.py

### Steps to run the scripts:
1) Run the server.py
2) Run client.py in the host machine/remote machine.
   * If you wanna run the client script in the host machine, open a new terminal window and run the client.py. Enter Host as '127.0.0.1' and Port as '33000'.
3) Tkinter GUI should open up. Chat away!
4) Hit Ctrl+C (Keyboard Interrupt) to exit the process in terminal.
 
 ### Output Screens:

![Screen1](Screenshots/Screen%201.png)

![Screen2](Screenshots/Screen%202.png)
 
 ### Features:
 - [x] Group Chat implemented.
 - [x] Text message support.
 - [x] Imgae Support.
 - [x] Video Chat.
 
 SocketChat.Py is inspired by : 
 https://medium.com/swlh/lets-write-a-chat-app-in-python-f6783a9ac170
 https://github.com/anilshanbhag/videochat
