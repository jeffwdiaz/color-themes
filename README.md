# My Custom Theme

A custom dark color theme for Visual Studio Code.

## Features

- Carefully selected dark color palette
- Custom syntax highlighting for comments, variables, keywords, strings, numbers, functions, and types
- Themed UI elements (activity bar, sidebar, status bar, title bar, etc.)

## Installation

### From VSIX (Local Install)

1. Install [vsce](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) if you haven't already:

   ```sh
   npm install -g vsce
   ```

2. Package the theme:

   ```sh
   vsce package
   ```

3. In VS Code or Cursor, open the Extensions sidebar (Ctrl+Shift+X), click the `...` menu, and select `Install from VSIX...`.
4. Choose the generated `.vsix` file to install.
5. Press `Ctrl+K Ctrl+T` and select "My Custom Theme".

## Development

- Edit `themes/my-custom-theme-color-theme.json` to tweak colors and token styles.
- Use an online theme previewer like [VS Code Theme Studio](https://themes.vscode.one/) or [vscodethemes.com/editor](https://vscodethemes.com/editor) to preview your color palette and syntax highlighting.
- For live preview as a full theme, package and install as above.

## Contributing

Pull requests are welcome! Please open an issue or discussion for major changes.

## License

MIT
