# 🔒 USB Protection System

A real-time USB monitoring and protection system built using **React**, **Node.js**, and **WebSocket**, designed to detect, block, and log unauthorized USB device access across Windows and Linux environments.

## 🚀 Features

- 🔍 Detects USB device connections/disconnections in real time
- 🔐 Classifies devices (HID, storage, charging-only)
- ✅ Admin-controlled whitelist and manual overrides
- 📊 Logs all activities (connects, blocks, allows)
- 🌐 Real-time frontend updates via WebSocket
- 🖥️ Cross-platform support (PowerShell + udevadm)
- 💾 Data stored persistently in JSON (`whitelist.json`, `logs.json`, etc.)

## 🧱 Tech Stack

| Layer        | Technologies                              |
|--------------|-------------------------------------------|
| **Frontend** | React, TypeScript, Tailwind CSS           |
| **Backend**  | Node.js, Express, usb-detection           |
| **Real-time**| WebSocket                                 |
| **OS Layer** | PowerShell (Windows), udevadm/lsblk (Linux) |
| **Storage**  | Local JSON files                          |





 

