# Noir Ivory — VS Code Theme Quickstart

Welcome to your custom theme extension. This project includes both variants of the theme:

- `Noir` — dark mode
- `Ivory` — light mode

## Project structure

* `package.json` — theme manifest and extension metadata
* `themes/Noir-color-theme.json` — dark theme definition
* `themes/Ivory-color-theme.json` — light theme definition

## Run the theme locally

1. Open this folder in VS Code.
2. Press `F5` to launch the Extension Development Host.
3. Open the Command Palette and run `Preferences: Color Theme`.
4. Select `Noir` or `Ivory`.

## Inspect tokens and scopes

To understand how colors are applied to syntax, open any file and run:

- `Developer: Inspect Editor Tokens and Scopes`

This is useful when refining semantic colors for keywords, strings, comments, and functions.

## Edit the theme

Changes to the theme JSON files are applied automatically in the Extension Development Host window.

If you want to refine the visual identity:

- adjust `colors` for editor UI surfaces
- adjust `tokenColors` for syntax highlighting
- keep contrast consistent across both variants

## Theme conventions

Noir Ivory follows a standard VS Code theme structure using TextMate scopes. Colors are assigned by token categories such as:

- comments
- strings
- keywords
- functions
- variables
- constants
- markup

For more information, see the official guide:

- [VS Code Color Theme documentation](https://code.visualstudio.com/api/extension-guides/color-theme)

## Install the extension

To install the packaged extension locally:

```bash
code --install-extension .\noir-ivory-theme-0.0.1.vsix
```

Or copy the `.vsix` to your VS Code extensions folder manually, then restart the editor.

## Publish

To share the theme with the world, package it and publish it through the VS Code Marketplace:

- [Publishing extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
