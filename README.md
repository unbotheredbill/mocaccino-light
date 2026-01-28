# Mocaccino Light

A warm, coffee-inspired light theme for Visual Studio Code.

## Color Palette

- **Background**: Creamy off-white (#FDF6E3)
- **Foreground**: Rich coffee brown (#5C4033)
- **Accent**: Saddle brown (#8B4513)
- **Keywords**: Bold coffee tones
- **Strings**: Olive green (#6B8E23)
- **Functions**: Steel blue (#4682B4)
- **Numbers**: Dark goldenrod (#B8860B)

## Installation

### From Source (Development)

1. Copy or clone this folder to your VS Code extensions directory:
   - **macOS**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **Linux**: `~/.vscode/extensions/`

2. Restart VS Code

3. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)

4. Type "Color Theme" and select "Preferences: Color Theme"

5. Select "Mocaccino Light"

### Quick Install (macOS)

```bash
cp -r "$(pwd)" ~/.vscode/extensions/mocaccino-light
```

Then restart VS Code and select the theme.

## Customization

Edit `themes/mocaccino-light-color-theme.json` to customize colors.

## Publishing

To publish to the VS Code Marketplace:

1. Install vsce: `npm install -g @vscode/vsce`
2. Create a publisher account at https://marketplace.visualstudio.com/manage
3. Update the `publisher` field in `package.json`
4. Run `vsce package` to create a `.vsix` file
5. Run `vsce publish` to publish
