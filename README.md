# HITMANGRABBER

## 🚀 Overview
Advanced Discord token extraction tool developed by **HITMAN** for security research and educational purposes. This tool scans multiple locations for Discord authentication tokens and sends detailed reports via Discord webhooks.

## ✨ Features
* **Multi-Source Scanning**: Extracts tokens from Discord desktop applications and browsers
* **Real-time Validation**: Verifies token validity through Discord API
* **Encrypted Token Decryption**: Decrypts protected tokens using Windows DPAPI
* **Rich Webhook Reports**: Sends formatted embeds with user avatars and detailed information
* **Stealth Operation**: Designed to avoid detection by security software

## 📁 Supported Sources

### Discord Applications
* Discord
* Discord Canary  
* Discord PTB
* Discord Development

### Browser Support
* Google Chrome
* Microsoft Edge
* Brave Browser
* Browser-based Discord clients

## 🔑 Token Types Extracted
* Standard authentication tokens (24.6.27 format)
* MFA-enabled tokens (mfa. format)
* Encrypted local storage tokens (dQw4w9WgXcQ format)

## 📊 Information Collected
* Authentication tokens
* Username and discriminator
* Email address
* Phone number (if available)
* User ID
* Avatar/profile picture
* 2FA status

## ⚙️ Installation & Usage

### Prerequisites
* Windows operating system
* Python 3.7+
* Discord webhook URL

### Setup
1. Configure your webhook URL in the script
2. Run the script - dependencies install automatically
3. Tokens are automatically sent to your webhook

### Webhook Configuration
```python
WEBHOOK_URL = "your_discord_webhook_url_here"
