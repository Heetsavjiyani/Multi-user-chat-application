💬 Real-time Multi-User Chat (Socket & Threading)
A foundational real-time chat application demonstrating direct network communication using Python's socket module and concurrent client handling via threading. It features a server that broadcasts messages, supports custom nicknames, and includes basic moderation commands.

✨ Features
1.Instant message exchange between multiple clients.
2.Server handles concurrent connections.
3.Clients use unique nicknames.
4.Messages broadcast to all participants.
5.Basic admin commands (e.g., /kick).

💻 Technologies
1.Python 3.x
2.socket module (Network communication)
3.threading module (Concurrency)

🚀 Getting Started
1.Clone the repository (ensure server.py and client.py are present).
2.Create and activate a virtual environment (as above).
3.No external dependencies required.
4.Open two (or more) separate terminal windows.
5.In the first terminal, run the server:
6.python server.py

In the second (and subsequent) terminals, run the client:
python client.py

Enter a nickname when prompted.
