# Online Chat Application

## 📌 Overview  
This is a simple **online chat application** built using **Java** and **socket programming**.  
It allows multiple users to connect to a central server, send messages, and receive messages from others.  

---

## ⚙️ Features  
✅ Supports multiple clients  
✅ Assigns a unique user ID to each client  
✅ Clients can send messages to all connected users  
✅ Commands:
- `!users` → View the list of online users  
- `!exit` → Leave the chat  
- `!help` → Show available commands  

---

## 🚀 How to Run  

### 1️⃣ Start the Server  
1. Open **PowerShell** or **Command Prompt** in the project folder.  
2. Navigate to the `src` directory:  
cd src

markdown
Copy
Edit
3. Compile the server:  
javac ChatServer.java

markdown
Copy
Edit
4. Run the server:  
java ChatServer

yaml
Copy
Edit

---

### 2️⃣ Start a Client  
1. Open a **new terminal** window.  
2. Navigate to the `src` directory:  
cd src

markdown
Copy
Edit
3. Compile the client:  
javac ChatClient.java

markdown
Copy
Edit
4. Run the client:  
java ChatClient

yaml
Copy
Edit
5. Repeat **Step 2** in another terminal to open multiple clients.  

---

## 🖥️ Example Output  

**Server Terminal:**  
✅ Server started on port 12345
📢 User1 has joined the chat!
📢 User2 has joined the chat!
💬 User1: Hello!
💬 User2: Hi there!

arduino
Copy
Edit

**Client 1 Terminal:**  
✅ Connected to the chat server!
Type your message or use commands: !users, !exit, !help
💬 User2: Hi there!

arduino
Copy
Edit

**Client 2 Terminal:**  
✅ Connected to the chat server!
Type your message or use commands: !users, !exit, !help
💬 User1: Hello!

yaml
Copy
Edit

---

## 📜 Notes  
- Ensure **Java is installed** (`java -version`).  
- Run the **server before** starting any client.  
- Clients must be on the **same network** to communicate.  
- The server **broadcasts messages** to all connected users.  

