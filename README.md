# Sails Theme for VS Code

[![Version](https://img.shields.io/visual-studio-marketplace/v/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/your-publisher-name.sails-theme)](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.sails-theme)

A professional, modern VS Code theme designed for optimal readability and reduced eye strain. Sails Theme offers carefully crafted color schemes in dark, light, and system-adaptive variants, inspired by the Sails.js framework's aesthetic.

![Sails Theme Preview](images/preview.png)

## Features

- 🎨 Three theme variants:
  - **Sails Dark**: Optimized for low-light environments
  - **Sails Light**: Perfect for bright workspaces
  - **Sails System**: Automatically adapts to your OS theme preferences
- 🎯 Language-optimized syntax highlighting
- 👀 High-contrast ratios for better readability (WCAG 2.1 AA compliant)
- 🖥️ Consistent UI elements across all VS Code panels
- ⚡ Semantic token support
- 🔄 Smooth transitions between theme variants

## Quick Start

### Installation

#### From VS Code Marketplace
1. Launch VS Code
2. Open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for "Sails Theme"
4. Click Install

#### From VSIX File (Development)
```bash
# Install from local VSIX
code --install-extension sails-theme-1.0.0.vsix
```

### Activation
1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Color Theme"
3. Choose one of:
   - "Sails Theme" (Dark variant)
   - "Sails Theme Light" (Light variant)
   - "Sails Theme (System)" (Follows system preferences)

## Testing Guide

### Local Development Testing
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sails-theme.git
   cd sails-theme
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Package the extension:
   ```bash
   vsce package
   ```

4. Install in VS Code:
   ```bash
   code --install-extension sails-theme-1.0.0.vsix
   ```

### Theme Testing Checklist

#### 1. Basic UI Elements
- [ ] Activity Bar visibility and contrast
- [ ] Sidebar readability
- [ ] Status Bar information clarity
- [ ] Panel titles and borders
- [ ] Tab active/inactive states
- [ ] Breadcrumbs navigation

#### 2. Editor Testing
- [ ] General text readability
- [ ] Line numbers visibility
- [ ] Current line highlight
- [ ] Selection highlight
- [ ] Find/Replace highlights
- [ ] Bracket matching
- [ ] Indentation guides

#### 3. Syntax Highlighting
Test with these file types:
- [ ] JavaScript/TypeScript
- [ ] HTML/CSS
- [ ] JSON/YAML
- [ ] Markdown
- [ ] Python
- [ ] Java
- [ ] XML

Check these elements:
- [ ] Comments
- [ ] Strings
- [ ] Numbers
- [ ] Keywords
- [ ] Functions
- [ ] Classes
- [ ] Variables
- [ ] Constants

#### 4. System Integration
- [ ] Dark mode transition
- [ ] Light mode transition
- [ ] System theme sync
- [ ] High contrast mode compatibility

#### 5. Accessibility Testing
- [ ] Color contrast ratios (WCAG 2.1 AA)
- [ ] Text readability in all sizes
- [ ] Icon visibility
- [ ] Error/warning highlighting
- [ ] Link visibility

## Color Palette

### Dark Theme
- Primary: `#47B4D1` (Sails Blue)
- Background: `#1B2B34` (Deep Ocean)
- Foreground: `#CDD3DE` (Soft Silver)
- Comments: `#627483` (Slate)
- Strings: `#99C794` (Seafoam)
- Keywords: `#47B4D1` (Sails Blue)
- Functions: `#47B4D1` (Sails Blue)
- Constants: `#FAC863` (Golden Sand)
- Error: `#EC5F67` (Coral Red)

### Light Theme
- Primary: `#47B4D1` (Sails Blue)
- Background: `#FFFFFF` (Pure White)
- Foreground: `#1B2B34` (Deep Ocean)
- Comments: `#A7ADBA` (Cool Gray)
- Strings: `#99C794` (Seafoam)
- Keywords: `#47B4D1` (Sails Blue)
- Functions: `#47B4D1` (Sails Blue)
- Constants: `#F99157` (Sunset Orange)
- Error: `#EC5F67` (Coral Red)

The color palette is carefully crafted to match the Sails.js brand identity while ensuring optimal readability and reduced eye strain. Each color has been selected to maintain WCAG 2.1 AA contrast ratios and provide a consistent, professional development experience.

## Customization

### Custom Settings
To customize specific colors, add the following to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Sails Theme]": {
      // Dark theme customizations
      "editor.background": "#1B2B34",
      "editor.foreground": "#CDD3DE"
    },
    "[Sails Theme Light]": {
      // Light theme customizations
      "editor.background": "#FFFFFF",
      "editor.foreground": "#1B2B34"
    }
  }
}
```

### Token Customization
For syntax highlighting customization:

```json
{
  "editor.tokenColorCustomizations": {
    "[Sails Theme]": {
      "comments": "#627483",
      "strings": "#99C794",
      "keywords": "#47B4D1"
    }
  }
}
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run the test checklist
5. Submit a pull request

Please ensure your PR adheres to:
- Consistent color palette usage
- Maintaining WCAG 2.1 AA contrast ratios
- Following semantic naming conventions
- Passing all test checklist items

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

- Inspired by [Sails.js](https://sailsjs.com/) framework's design
- Color science research from [Color Research and Application Journal](https://onlinelibrary.wiley.com/journal/15206378)
- Feedback from the VS Code community

## Support

- File issues on [GitHub](https://github.com/yourusername/sails-theme/issues)
- Follow updates on [Twitter](https://twitter.com/yourusername)
- Join our [Discord community](https://discord.gg/yourdiscord)

---

**Made with ❤️ by developers, for developers**

*Note: Replace all placeholder URLs, usernames, and social media links with your actual information before publishing.*
