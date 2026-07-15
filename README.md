# 🤖 Aternos 24/7 Bot

This project creates a Minecraft bot that joins your Aternos server and stays active by moving, chatting, and reconnecting automatically. It is designed for keeping a small server online when no players are present.

## ✅ What it does
- Joins your Aternos server automatically
- Sends AFK movement so the server stays active
- Reconnects if the connection drops
- Exposes a small dashboard and health endpoint
- Works well for Render or other 24/7 hosting setups

## ⚙️ Quick start on Windows
1. Install Node.js from https://nodejs.org/
2. Open the bot folder in Command Prompt or PowerShell
3. Edit the server details in settings.json
4. Run start.bat

If you prefer PowerShell, run:
- powershell -ExecutionPolicy Bypass -File .\start.ps1

## 🔧 Aternos setup tips
- Make sure your Aternos server is already online before launching the bot
- Enable cracked mode if your server requires it
- Use the correct IP, port, and version in settings.json
- If the bot cannot join, double-check that the username and server address are correct

## 🚀 24/7 hosting
For true 24/7 uptime, deploy this project to a host such as Render, Railway, or a VPS. The included self-ping logic helps keep the service awake while the bot remains connected.

## ⚠️ Disclaimer
This project is not affiliated with Aternos, Mojang, or Microsoft. Use it responsibly and follow the platform rules.
