# Contributing to Coursera AI Instructions Remover

Thank you for your interest in contributing to this project! This document provides guidelines and information for contributors.

## How to Contribute

### Reporting Issues

If you find a bug or have a feature request, please open an issue on GitHub with:

1. A clear and descriptive title
2. Detailed description of the issue or feature request
3. Steps to reproduce the issue (if applicable)
4. Expected behavior vs. actual behavior
5. Screenshots if applicable
6. Browser version and extension version information

### Pull Requests

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes
4. Test your changes thoroughly
5. Commit your changes with a clear commit message
6. Push to your fork and submit a pull request

### Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/S1ii/coursera-ai-instructions-remover.git
   cd coursera-ai-instructions-remover
   ```

2. Load the extension in your browser:
   - Open Chrome/Edge and go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the project directory

### Code Style

- Use consistent indentation (2 spaces)
- Follow JavaScript best practices
- Add comments for complex logic
- Keep functions small and focused

### Testing

- Test the extension on different Coursera pages
- Verify that the extension works with different browser versions
- Test both light and dark themes
- Test language switching functionality

## Project Structure

```
coursera-ai-instructions-remover/
├── manifest.json          # Extension manifest
├── background.js          # Service worker
├── content.js             # Content script
├── popup.html             # Popup interface
├── popup.js               # Popup logic
├── locales.js             # Localization
├── icons/                 # Extension icons
│   ├── icon16.svg
│   ├── icon48.svg
│   └── icon128.svg
└── docs/                  # Documentation
```

## License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.