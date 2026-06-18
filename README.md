# WhatsApp Baileys

<p align="center">
  <img src="https://raw.githubusercontent.com/xyroorynzz/image/main/alice.jpg" width="300"/>
</p><p align="center">
  <b>Enterprise-Grade WhatsApp Bot Library</b><br>
  High-performance Baileys wrapper for scalable WhatsApp automation
</p><p align="center">
  <img src="https://img.shields.io/badge/Node.js-v20+-green?style=flat-square">
  <img src="https://img.shields.io/badge/Modified-Baileys-blue?style=flat-square">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square">
</p>

# Overview

WhatsApp Baileys adalah library open-source berbasis Baileys yang telah dimodifikasi untuk kebutuhan automation dan integrasi WhatsApp skala besar.

Dirancang agar ringan, cepat, dan mudah digunakan, serta mendukung berbagai fitur terbaru dari WhatsApp Multi-Device.

---

# Features

- Custom & automatic pairing
- Interactive message & action buttons
- Album message (multiple images)
- Event message
- Poll result message
- Product message
- Payment request message
- Group & chat management
- Multi-device support
- Lightweight & scalable

---

# Installation

npm install alice-baileys@latest

---

# Usage

import makeWASocket from 'alice-baileys'

const sock = makeWASocket()

sock.ev.on('messages.upsert', async (msg) => {
  console.log(msg)
})

---

# License

MIT License © 2026