# Claude.ai Ultimate Chat Exporter Plus

An enhanced userscript for exporting chat conversations from Claude.ai, building upon the excellent foundation of the original Claude.ai Ultimate Chat Exporter.

## Features

- Export individual chats in JSON or TXT format
- Export all chats at once from the chats overview page
- Clean and intuitive interface with integrated export buttons
- Preserves complete conversation history with timestamps
- Handles large chat histories efficiently

## Installation

1. Install a userscript manager for your browser:
   - [Tampermonkey](https://www.tampermonkey.net/) (recommended)
   - [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
   - [Violentmonkey](https://violentmonkey.github.io/)

2. Install the script:
   - Click [here](#) to install (GreasyFork link coming soon)
   - Or copy the script content and create a new userscript in your userscript manager

## Usage

1. Navigate to [Claude.ai](https://claude.ai/)
2. For individual chats:
   - Open any chat
   - Click the "Export Chat" button
   - Choose your preferred format (JSON or TXT)

3. For all chats:
   - Go to the chats overview page (https://claude.ai/chats)
   - Click the "Export All Chats" button
   - Choose your preferred format

## Output Formats

### JSON Format
- Complete conversation data including:
  - Message content
  - Timestamps
  - Conversation metadata
  - Perfect for programmatic processing or backup

### TXT Format
- Clean, readable format
- Messages clearly labeled with "User:" and "Claude:"
- Ideal for reading or sharing conversations

## Credits

This project is a fork of [Claude.ai Ultimate Chat Exporter](https://github.com/GeoAnima/claude.ai-ultimate-chat-exporter) by Geo Anima, licensed under the MIT License. Original functionality and core implementation by Geo Anima.

Enhanced and maintained by [Doug Mortensen](https://github.com/ExactDoug).

## Development Roadmap

Planned enhancements include:
- [ ] Markdown export format
- [ ] Custom file naming templates
- [ ] Export progress indicators
- [ ] Batch export options with filters
- [ ] Enhanced error handling and recovery
- [ ] Export formatting customization

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Doug Mortensen
Original work Copyright (c) 2024 Geo Anima

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Changelog

### Version 1.1
- Initial fork from Claude.ai Ultimate Chat Exporter
- Updated metadata and documentation
- Added enhanced development roadmap
- Improved installation instructions

### Version 1.0
- Original release by Geo Anima