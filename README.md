# 📂 File Transfer System (Java, Networking)

A **client-server based File Transfer System** built in **Java** using **TCP sockets**.  
This project allows a client to request files from a server over the network. It supports **file listing, multiple file downloads, and pause/resume functionality** for large file transfers.  

---

## 🚀 Features
- 📁 List available files from the server  
- ⬇️ Download single or multiple files  
- ⏸️ Pause & Resume large file transfers  
- ⚡ Multithreaded server for handling multiple clients  
- 🔄 Reliable TCP-based file transfer ensuring data integrity  

---

## 🛠️ Technologies Used
- Java SE (Core Java)  
- TCP/IP Networking (Sockets)  
- Multithreading  
- File I/O (Streams, Buffers)  

---

## 📖 How It Works
1. **Server** starts and listens on a port for incoming connections.  
2. **Client** connects to the server and requests a file or file list.  
3. **Server** sends the requested file in chunks over TCP.  
4. **Client** saves the file locally, with the ability to **pause and resume** transfers.  

---

## ▶️ Usage
### 1️⃣ Run the Server
```bash
javac FileTransferServer.java
java FileTransferServer

