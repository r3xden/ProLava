<p align="center">
  <img src="assets/prolava-logo.jpg" width="180" alt="ProLava Logo" />
</p>

<h1 align="center">🔥 ProLava</h1>
<p align="center"><b>Best open-source Lavalink template for learning & instant deployment</b></p>

<p align="center">
  Fork → Configure → Deploy → Connect → Stream
</p>

---

## 🚀 What is ProLava?

ProLava is a production-ready, open-source Lavalink server template designed for:

✅ Beginners learning Discord music bots  
✅ Developers who want instant Lavalink setup  
✅ Public bot owners who need stable infrastructure  
✅ Open-source contributors  

It gives you everything needed to run your own Lavalink server in minutes with clean configs, Docker, VPS guides, and full documentation.

---

## 🎧 What is Lavalink?

Lavalink is an audio streaming server for Discord music bots.

Bot → Sends request → Lavalink streams audio → Discord plays audio

Supported sources:
- YouTube  
- SoundCloud  
- HTTP streams  
- Twitch  
- Vimeo  
- Playlists & filters  

---

## 🎯 Why ProLava?

Most people fail Lavalink setup because of:

❌ Confusing Java setup  
❌ Broken configs  
❌ No Docker support  
❌ No proper docs  
❌ Unsafe public nodes  

ProLava fixes all of this with:

✅ Clean folder structure  
✅ Beginner-safe application.yml  
✅ Docker + VPS full guides  
✅ Render deployment support  
✅ Contributor guide  
✅ MIT license  

---

## 📂 Project Structure

```bash
ProLava/
├── .github/
│   └── FUNDING.yml
├── configs/
│   └── application.example.yml
├── assets/
│   └── prolava-logo.jpg
├── application.yml
├── docker-compose.yml
├── start.sh
├── start.bat
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Manual VPS Setup (Linux / Ubuntu)

1. Update server  
sudo apt update && sudo apt upgrade -y

2. Install Java 17  
sudo apt install openjdk-17-jdk -y

3. Verify Java  
java -version

4. Download Lavalink  
wget https://github.com/lavalink-devs/Lavalink/releases/latest/download/Lavalink.jar

5. Edit password in application.yml  
password: "changeme"  
→ change to something secure

6. Start ProLava  
java -jar Lavalink.jar

✅ Runs on:  
http://YOUR_VPS_IP:2333

---

## 🐳 Docker Deployment (Recommended)

1. Install Docker  
sudo apt install docker docker-compose -y

2. Start ProLava  
docker-compose up -d

✅ Auto restart  
✅ No Java install needed  
✅ Production safe  

---

## ☁️ Render Deployment Guide

1. Go to: https://render.com  
2. Create New Web Service  
3. Choose Docker  
4. Select your ProLava repo  
5. Add environment variable:  
LAVALINK_SERVER_PASSWORD=yourpassword  
6. Expose port:  
2333  
7. Click Deploy  

✅ ProLava will go live in minutes.

---

## 🖼️ Official Docker Image

ProLava uses the official Lavalink image:

ghcr.io/lavalink-devs/lavalink:latest

✅ Verified  
✅ Secure  
✅ Maintained by Lavalink devs  

---

## 🔗 Connect Your Bot to ProLava

Node.js:
host: YOUR_IP  
port: 2333  
password: yourpassword  
secure: false  

Python:
uri: http://YOUR_IP:2333  
password: yourpassword  

---

## 🔐 Security Guidelines

- Always change default password  
- Never expose Lavalink without firewall  
- Use SSL for public bots  
- Never publish open public Lavalink nodes  

---

## 🧑‍💻 Contributor Guide

Rules:
- Use clean commits
- Follow file structure
- Document all changes
- Avoid breaking configs

Flow:
1. Fork the repo  
2. Create a new branch  
3. Make changes  
4. Commit with clear message  
5. Open a pull request  

---

## 📜 License

MIT License — Free to use, modify, distribute & commercialize.

## © Copyright & Trademark Disclaimer

© 2025 ProLava. All rights reserved.

"ProLava" is a project name and brand identity created and maintained by Rexden.  
This repository is open-source under the MIT License; however, the **name, logo, and branding of ProLava are protected for brand identity purposes**.

You are free to:
- Use the source code
- Modify and distribute it
- Use it for personal or commercial projects

You are **NOT permitted to**:
- Impersonate ProLava as an official product
- Use the ProLava name/logo for misleading distribution
- Claim official ownership of the ProLava brand

This protects ProLava for:
- Brand registration
- Public identity
- Future commercial usage

---

## 🎨 Branding & Credits

ProLava — Created & maintained by Rexden  
Lavalink Engine — by lavalink-devs  
Community contributors & open-source supporters  

---

## ⭐ Support the Project

If ProLava helped you:

⭐ Star the repository  
🍴 Fork it  
📢 Share it  
🛠 Contribute  

---

ProLava — Powering the next generation of Discord music bots.
