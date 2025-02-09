# VSCode Jupyter to Colab Keybindings

This repository contains keyboard shortcuts configuration files that make VSCode's Jupyter notebook experience more similar to Google Colab's keyboard shortcuts. This is particularly helpful for users who frequently switch between both environments.

## Available Configurations

- `vscode_jupyter_to_colab_keybindings_mac.json` - For macOS users
- `vscode_jupyter_to_colab_keybindings_windows.json` - For Windows users

## Installation

1. Open Visual Studio Code
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Windows) to open the Command Palette
3. Type "Preferences: Open Keyboard Shortcuts (JSON)" and select it
4. Copy the contents from the appropriate JSON file (Mac or Windows) into your keybindings.json
5. Save the file

## Included Shortcuts

These keybindings mirror Google Colab's most common shortcuts:

- `Cmd/Ctrl + Enter` - Run current cell
- `Shift + Enter` - Run current cell and select below
- `Alt + Enter` - Run current cell and insert below
- `Cmd/Ctrl + M A` - Insert cell above
- `Cmd/Ctrl + M B` - Insert cell below
- `Cmd/Ctrl + M D` - Delete current cell
- And more...

## Contributing

Feel free to submit issues or pull requests if you have suggestions for additional Colab-like shortcuts or improvements. 