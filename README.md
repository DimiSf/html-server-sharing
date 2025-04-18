# 🌐 html-server-sharing
A simple project to serve files and images over a local network using Python’s HTTP server.

## 📦 Files
- `index.html`: Main page with links to downloadable content
- `hello.txt`: Example text file
- `image.png`: Example image

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/*your-username*/html-server-sharing.git
   cd html-server-sharing
   
-----------------------------------------------------------------------------------------------

2. Start the server:

   ```bash
   python3 -m http.server 8000

3. Find your IP address:

   ```bash
   hostname -I

4. From another device on the same Wi-Fi, open in browser:

   ```bash
   http://<your-ip>:8000
