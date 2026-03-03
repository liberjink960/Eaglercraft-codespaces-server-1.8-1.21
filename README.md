# Eaglercraft Server, 1.8 and 1.12.2 compatible - Codespaces Edition

A complete setup for running an Eaglercraft server in GitHub Codespaces, compatible with Minecraft versions 1.8-1.21.

## Features

- ✅ Configurable MOTD (Message of the Day)
- ✅ Max Players control via `server.properties`
- ✅ Multi-version support (1.8-1.21)
- ✅ Codespaces-ready with automated setup
- ✅ Easy port forwarding configuration

## Quick Start

1. **Create Codespace**: Click "Code" → "Codespaces" → "Create codespace on main"
2. **Wait for setup**: The devcontainer will automatically install Java and dependencies
3. **Start server**: Run `./start.sh`
4. **Access server**: Check the "Ports" tab for your forwarded port

## Configuration

Edit `server.properties` to customize:
- `motd` - Server message (supports color codes like §a, §c, §l)
- `max-players` - Maximum concurrent players
- `gamemode` - survival, creative, adventure, or spectator
- `difficulty` - peaceful, easy, normal, or hard
