# Sails Theme for VS Code

[![Version](https://img.shields.io/visual-studio-marketplace/v/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)

A professional, modern VS Code theme designed for optimal readability and reduced eye strain. Sails Theme offers carefully crafted color schemes in dark, light, and system-adaptive variants.

![Sails Theme Preview](images/preview.png)

## Features

- 🎨 Three theme variants:
  - **Sails Dark**: Optimized for low-light environments
  - **Sails Light**: Perfect for bright workspaces
  - **Sails System**: Automatically adapts to your OS theme preferences
- 🎯 Language-optimized syntax highlighting
- 👀 High-contrast ratios for better readability
- 🖥️ Consistent UI elements across all VS Code panels
- ⚡ Semantic token support
- 🔄 Smooth transitions between theme variants

## Installation

1. Launch VS Code
2. Open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for "Sails Theme"
4. Click Install

Alternatively, you can install it directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme).

## Usage

1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Color Theme"
3. Choose one of:
   - "Sails Theme" (Dark variant)
   - "Sails Theme Light" (Light variant)
   - "Sails Theme (System)" (Follows system preferences)

## Color Palette

### Dark Theme
- Background: `#001c20`
- Foreground: `#8adae6`
- Accent: `#14acc2`
- Comments: `#2e484f`
- Strings: `#0c8da0`
- Keywords: `#14acc2`
- Functions: `#14acc2`
- Variables: `#8adae6`

### Light Theme
- Background: `#ffffff`
- Foreground: `#001c20`
- Accent: `#14acc2`
- Comments: `#6e8a91`
- Strings: `#0c8da0`
- Keywords: `#14acc2`
- Functions: `#14acc2`
- Variables: `#006d7d`

## Supported Languages

Optimized syntax highlighting for:
- JavaScript/TypeScript
- Python
- Java
- C/C++
- HTML/CSS
- JSON
- Markdown
- And many more...

## Customization

To customize specific colors, add the following to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Sails Theme]": {
      // Your customizations here
    }
  }
}
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Please ensure your PR adheres to:
- Consistent color palette usage
- Maintaining WCAG 2.1 AA contrast ratios
- Following semantic naming conventions

## Development

```bash
# Install dependencies
npm install

# Package the extension
vsce package

# Install the extension locally
code --install-extension sails-theme-1.0.0.vsix
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by maritime themes and professional IDEs
- Color science research from [Color Research and Application Journal](https://onlinelibrary.wiley.com/journal/15206378)
- Feedback from the VS Code community

## Support

- File issues on [GitHub](https://github.com/yourusername/sails-theme/issues)
- Follow updates on [Twitter](https://twitter.com/yourusername)
- Join our [Discord community](https://discord.gg/yourdiscord)

---

**Made with ❤️ by developers, for developers**

*Note: Replace all placeholder URLs, usernames, and social media links with your actual information before publishing.*
