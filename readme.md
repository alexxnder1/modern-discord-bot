## Overview

**Eastern Games Bot** is a Discord bot built with Node.js and JavaScript that provides moderation tools, music playback, and general utility commands for managing and automating a server. The project is structured to be modular, making it easy to extend or adapt for custom features and workflows. It runs on the Discord API through libraries from **:contentReference[oaicite:0]{index=0}** and the Discord ecosystem.

---

## Features

### Moderation & Server Management
- User and role management commands  
- Server utilities and automation tools  
- Slash and prefix command support  

### Music Playback
- Stream audio in voice channels  
- Queue, skip, and playback controls  
- Powered by DisTube and Discord music libraries  

### Dynamic Content
- Generate images and graphics (welcome cards, banners, stats, etc.) using Canvas  

### Database Support
- Persistent storage with MongoDB via Mongoose  
- Saves settings, configurations, and user data  

### HTTP & Integrations
- External API requests using axios and undici  
- Environment configuration with dotenv  

---

## Tech Stack

- **Node.js** – runtime  
- **discord.js** – Discord API wrapper  
- **@discordjs/rest** – REST interactions and command registration  
- **distube / discord-music-player** – music system  
- **@distube/yt-dlp & @discordjs/opus** – audio streaming/decoding  
- **canvas / @napi-rs/canvas** – image generation  
- **mongoose (MongoDB)** – database layer  
- **axios / undici** – HTTP requests  
- **dotenv** – environment variables  

---

## Purpose

This repository serves as a ready-to-run foundation for a multi-purpose Discord bot, covering common server needs while remaining easy to modify and expand.
