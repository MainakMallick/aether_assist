# Aether Assistant

A powerful desktop AI assistant that provides real-time screenshot analysis and intelligent responses using Google's Gemini AI.

![Aether Assistant](assets/logo.png)

## Features

- 🔍 **Real-time Screenshot Analysis**: Capture and analyze any part of your screen
- 🤖 **AI-Powered Responses**: Powered by Google's Gemini AI for intelligent analysis
- 🎯 **Floating Window Interface**: Always accessible, never intrusive
- 🔐 **Secure Authentication**: Google Sign-in integration with Firebase
- ⚡ **Customizable Shortcuts**: Personalize your experience with custom keyboard shortcuts
- 🌓 **Transparency Controls**: Adjust window opacity for better visibility
- 💻 **Cross-Platform**: Works on Windows, macOS, and Linux

## Installation

### Windows
1. Download the latest release from the [Releases](https://github.com/yourusername/aether-assistant/releases) page
2. Choose between:
   - `Aether-Assistant-Setup-x.x.x.exe` (Installer)
   - `Aether-Assistant-Portable-x.x.x.exe` (Portable version)

### macOS
1. Download the latest `.dmg` file from the [Releases](https://github.com/yourusername/aether-assistant/releases) page
2. Mount the DMG and drag Aether Assistant to your Applications folder

### Linux
1. Download the latest `.AppImage` from the [Releases](https://github.com/yourusername/aether-assistant/releases) page
2. Make it executable: `chmod +x Aether-Assistant-x.x.x.AppImage`
3. Run the AppImage

## Development Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/aether-assistant.git
cd aether-assistant
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```env
GEMINI_API_KEY=your_gemini_api_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

4. Start the development server:
```bash
npm start
```

## Building

### Windows
```bash
# Build installer
npm run build-installer

# Build portable version
npm run build-portable

# Build both
npm run build-all
```

### macOS
```bash
npm run build
```

### Linux
```bash
npm run build
```

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Desktop Framework**: Electron.js
- **Backend**: Node.js
- **Authentication**: Firebase Authentication, Google OAuth2.0
- **Database**: Firebase Firestore
- **AI Integration**: Google Gemini AI
- **Build Tools**: Electron Builder
- **Package Management**: npm

## Keyboard Shortcuts

- `Alt + T`: Toggle window transparency
- `Alt + S`: Capture and analyze screenshot
- Custom shortcuts can be configured in the settings

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Electron](https://www.electronjs.org/)
- [Firebase](https://firebase.google.com/)
- [Google Gemini AI](https://ai.google.dev/)
- [Highlight.js](https://highlightjs.org/)
- [Marked](https://marked.js.org/)

## Support

For support, please open an issue in the GitHub repository or contact [your-email@example.com](mailto:your-email@example.com) 
