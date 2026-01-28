🔐 AEGIS License Management System

🌐 Live Demo: https://guardrailengine.github.io/-/

A modern, secure license key generation and cloud management system with a sleek hacker-inspired interface.

✨ Features

Core Features

· ✅ Secure Key Generation - Generate cryptographically secure license keys
· ✅ Cloud Synchronization - Real-time sync with cloud database
· ✅ Responsive Design - Works on desktop, tablet, and mobile
· ✅ Clipboard Integration - One-click copy to clipboard
· ✅ Visual Feedback - Animated status indicators
· ✅ Demo Mode - Safe demonstration without real API keys

Security Features

· 🔒 Cryptographically secure random number generation
· 🔒 Frontend/Backend separation in architecture
· 🔒 No sensitive data exposed in client-side code
· 🔒 Production-ready security patterns

🛠️ Tech Stack

Layer Technologies
Frontend HTML5, CSS3, JavaScript (ES6+)
Styling CSS Grid, Flexbox, CSS Variables
Icons Font Awesome 6
Database PostgreSQL (via Supabase)
API REST Architecture
Security Web Crypto API

🚀 Getting Started

Quick Start

1. Download or clone the project
2. Open index.html in any modern browser
3. Start generating license keys!

For Developers

```bash
# Clone the repository
git clone https://github.com/GuardrailEngine/GuardrailEngine.git

# Navigate to project directory
cd GuardrailEngine

# Open in browser or use local server
# Option 1: Direct file opening
# Option 2: Using Python HTTP server
python -m http.server 8000
# Then visit: http://localhost:8000
```

📖 How to Use

Step 1: Generate a Key

1. Click "Generate License Key" button
2. Wait for the key to generate (takes ~1 second)
3. Generated key format: AEGIS-XXXXXX-2026

Step 2: Sync to Cloud

1. Click "Sync to Cloud Vault" button
2. Watch the sync status in real-time
3. On success, button turns green

Copy Key to Clipboard

· Click "Copy to Clipboard" button
· The key will be copied automatically
· Paste anywhere (Ctrl+V or Cmd+V)

⚠️ Important Note

This is a DEMO version for portfolio and educational purposes.
Production implementation requires:

· Backend server (Node.js, Python, etc.)
· User authentication system
· Encrypted database storage
· SSL/TLS encryption
· Rate limiting and security headers

🔧 How It Works

Key Generation

· Uses crypto.getRandomValues() for secure randomness
· Generates 6-character alphanumeric codes
· Follows format: AEGIS-{RANDOM6}-2026

Cloud Integration

· Simulated cloud sync in demo mode
· Demonstrates REST API concepts
· Shows database integration patterns

User Interface

· Responsive design using CSS Grid/Flexbox
· Hacker-themed color scheme (#D4AF37 gold, #00f2ff cyan)
· Smooth animations and transitions
· Works on all device sizes

📱 Browser Support

Browser Version Status
Chrome 90+ ✅ Full support
Firefox 88+ ✅ Full support
Safari 14+ ✅ Full support
Edge 90+ ✅ Full support

🏗️ Project Structure

```
GuardrailEngine/
├── index.html              # Main application file
├── README.md               # This documentation file
└── screenshot.jpg          # System screenshot (optional)
```

👨‍💻 Developer

Your Name
GitHub: @GuardrailEngine
LinkedIn: Your LinkedIn Profile

🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

📄 License

This project is for educational purposes. Feel free to use and modify for learning.

---

🌟 Show Your Support

Give a ⭐️ to this repository if you find it helpful!

---

Last updated: January 2026
