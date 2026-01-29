# hockeyteambuilding

I'll create an interactive hockey game for you! Let me build this with HTML, Tailwind CSS, and JavaScript.I've created an interactive hockey game! Here's what it includes:

**Features:**
- 🏒 Two-player local multiplayer
- ⚫ Physics-based puck with momentum and friction
- 🥅 Goals on both sides with score tracking
- 🎮 Smooth player controls
- 🎨 Ice rink design with center line and circle

**How to Play:**
- **Player 1 (Blue):** Use WASD keys to move
- **Player 2 (Red):** Use Arrow keys to move
- Push the puck into your opponent's goal to score
- Click "Start Game" to begin

The game features collision detection between players and the puck, realistic puck physics with friction, and automatic score tracking. Players bounce the puck off the walls and try to shoot it into the opponent's goal!

Perfect! I've created **CORAL TEAM Hockey - Online Multiplayer Edition** with full browser-to-browser networking! 🏒🌐

## 🌐 ONLINE MULTIPLAYER FEATURES:

**Host a Game:**
1. Click "HOST GAME"
2. Enter your name
3. Select your team (Coral or Storm)
4. Get a unique **Game Key** (automatically generated)
5. Share the key with friends
6. Wait for players to join
7. Click "START GAME" when ready!

**Join a Game:**
1. Click "JOIN GAME"
2. Enter your name
3. Enter the **Game Key** from the host
4. Select your team
5. Click "CONNECT"
6. Wait for host to start the game!

## ⚡ KEY FEATURES:

**Real-Time Multiplayer:**
- ✅ Uses **PeerJS** for WebRTC peer-to-peer connections
- ✅ No server needed - direct browser-to-browser communication
- ✅ Host controls game physics and scoring
- ✅ Clients send input and receive game state
- ✅ 20 updates per second for smooth gameplay

**Visual Indicators:**
- ✅ **Your player glows yellow** so you can easily spot yourself
- ✅ Player names displayed above characters
- ✅ Connection status shown in header
- ✅ Active players list shows all participants
- ✅ Team player counts updated in real-time

**Game Management:**
- ✅ Copy game key button for easy sharing
- ✅ See who's connected before starting
- ✅ Automatic disconnection handling
- ✅ Both WASD and Arrow keys work for all players

**How It Works:**
- Host creates a peer connection and generates a game ID
- Other players connect to the host using that ID
- Host runs the game simulation (physics, collisions, scoring)
- Clients send their input to the host
- Host broadcasts game state to all clients
- Everyone sees synchronized gameplay!

Share the game key with friends and play together from different computers or browsers! 🎮✨