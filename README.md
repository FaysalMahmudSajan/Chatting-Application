# Project : Chatting Application 


![img](ActivityDiagram.png)
![img](usecasediagram.png)
![Alt Text](classDiagram.png)


## 🎯 How It Works

### Server
1. Server starts and listens on port **6002**
2. Waits for client connection
3. Once connected, messages are exchanged
4. Broadcasts messages to connected client

### Client
1. Client connects to server at `127.0.0.1:6002`
2. Establishes socket connection
3. Sends and receives messages
4. Displays messages with timestamps

## 🚀 Installation & Setup

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- NetBeans IDE (optional, can run from command line)

### Steps to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/FaysalMahmudSajan/Chatting-Application.git
   cd Chatting-Application

   ```