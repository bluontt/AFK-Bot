
# AFK Bot v1.0

A sophisticated AFK (Away From Keyboard) bot for gaming with KeyAuth authentication, designed to keep your character active while you're away.



## Features

- 🔐 **Secure Authentication** - KeyAuth integration for license validation
- 🖱️ **Mouse Rotation** - Smooth, natural mouse movements
- ⌨️ **Key Sequences** - Randomized key presses to simulate gameplay
- 💬 **Chat Messages** - Sends random chat messages to maintain presence
- ⏸️ **Pause/Resume** - Right Shift hotkey for quick control
- 🎨 **Modern UI** - Dark themed interface with real-time status updates
- 📊 **Activity Logging** - Detailed logs of all bot activities
- ⚙️ **Customizable Settings** - Adjustable delays and feature toggles

## Requirements

- Python 3.11 or higher
- Windows/Linux/macOS
- Valid KeyAuth license key
- Internet connection for authentication

## Quick Setup

### Automatic Setup (Recommended)

**Windows:**
```batch
setup.bat
```

## Getting Started

### 1. Obtain License Key
- Contact the bot administrator for a valid license key
- Each license is tied to your hardware ID (HWID)

### 2. Authentication
1. Launch the bot
2. Enter your license key in the authentication section
3. Click "Authenticate"
4. Wait for successful authentication

### 3. Configure Settings
- **Enable Chat Messages**: Toggle automatic chat messages
- **Enable Mouse Rotation**: Toggle mouse movement simulation
- **Action Delay**: Adjust timing between actions (0.1-5.0 seconds)

### 4. Start Bot
1. Click "Start AFK" after successful authentication
2. Use Right Shift key to pause/resume anytime
3. Click "Stop" to completely stop the bot


## Controls

| Key | Action |
|-----|--------|
| Right Shift | Pause/Resume bot |
| Start AFK | Begin all bot activities |
| Pause | Pause bot (same as Right Shift) |
| Stop | Completely stop all activities |

## Bot Actions

### Movement Simulation
- **WASD Keys**: Random movement patterns
- **Mouse Rotation**: Smooth circular movements around screen center
- **Jump/Crouch**: Space and Ctrl keys
- **Interaction**: E, Q, V keys
- **Mouse Clicks**: Left and right click simulation

### Chat System
- Sends random gaming-related messages
- 30-60 second intervals between messages
- Over 50 different preset messages
- Avoids repeating the same message consecutively

## Troubleshooting

### Common Issues

**Authentication Failed**
- Check internet connection
- Verify license key is correct
- Ensure license hasn't expired
- Contact support if HWID changed

**Bot Not Working**
- Make sure the game window is active
- Verify screen resolution is detected correctly
- Try adjusting action delays

**Performance Issues**
- Close unnecessary applications
- Reduce action frequency
- Disable unused features (chat/mouse rotation)

### Error Messages

| Error | Solution |
|-------|----------|
| "Connection timeout" | Check internet/firewall settings |
| "Invalid server response" | Try again later, server may be busy |
| "HWID mismatch" | Contact support for license reset |
| "Screen detection error" | Restart application |

## Safety Features

- **Failsafe Protection**: PyAutoGUI failsafe prevents runaway automation
- **Smooth Movements**: Natural-looking mouse movements
- **Random Delays**: Variable timing to avoid detection
- **Pause Functionality**: Instant pause with hotkey
- **Error Handling**: Comprehensive error catching and logging

## System Information

The bot automatically detects and logs:
- Hardware ID (HWID) for authentication
- Screen resolution
- Operating system details
- Available input methods


## Legal Notice

This software is for educational and authorized testing purposes only. Users are responsible for complying with:
- Game Terms of Service
- Local laws and regulations
- Fair play policies

Use at your own risk. The developers are not responsible for any consequences of using this software.

## Support

For technical support or license issues:
1. Check this README for common solutions
2. Review the activity log for error details
3. Contact the bot administrator with your KEY
4. Provide detailed error descriptions

## Version History

### v1.0
- Initial release


**© 2025 BluXploit - Blu Services & Nexus Prime**

*Remember: Always use responsibly and in accordance with game rules and terms of service.*
