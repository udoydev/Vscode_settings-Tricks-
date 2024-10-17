# Vscode_settings-Tricks-
All About vs code settings
## Fonts 
### SF MONO , INTER (download from folder section)
### If your fonts look pixelated watcht this video : 
[Link](https://youtu.be/YRqoVG-ApSI?si=fQCmSMgxeR5ywkxy)
### Vs Code Settings.json code UI
``` 
{
  // Font settings for better readability and smoothness
  "editor.fontFamily": " 'SF Mono', 'Roboto Mono','Inter', 'Fira Code', Consolas, 'Courier New', monospace",

  "editor.fontLigatures": true,

  "editor.fontSize": 15,
  "editor.fontWeight": "400",
  "editor.lineHeight": 24, // Adds breathing space between lines
  "editor.letterSpacing": 0.5, // Slightly increased spacing for comfort

  // Enable smooth scrolling for a better experience
  "editor.smoothScrolling": true, // Keep the status bar for essential info
  "editor.minimap.enabled": false, // Disable minimap for less clutter
  "breadcrumbs.enabled": false, // Disable breadcrumbs for simplicity
  "editor.cursorBlinking": "smooth", // Smooth cursor motion for ease on the eyes
  "editor.renderWhitespace": "boundary", // Show only important whitespace markers

  // Better contrast and comfortable theme
  "workbench.colorTheme": "Monokai Pro (Filter Octagon)", // You can change this to your preferred theme
  "editor.cursorStyle": "line-thin", // Adjust the zoom level for readability, increase if necessary

  // Code folding and indentation guides for better code organization
  "window.zoomLevel": 1,
  "editor.folding": true, // Enable code folding to hide unnecessary sections
  "editor.guides.indentation": true, // Show indentation guides for clarity
  "editor.autoIndent": "full", // Enable full automatic indentation for better structure

  // Zen Mode settings for focused coding sessions
  "zenMode.hideActivityBar": true, // Hide activity bar in Zen mode for focus
  "zenMode.hideLineNumbers": false, // Keep line numbers visible in Zen mode
  "zenMode.hideStatusBar": true, // Hide status bar during Zen mode
  "zenMode.restore": true, // Automatically restore when exiting Zen mode

  // Miscellaneous settings to enhance user comfort
  "editor.lineNumbers": "on", // Keep line numbers visible for navigation
  "editor.renderLineHighlight": "all", // Smooth caret animation when navigating
  "editor.tabSize": 4, // Standard tab size for consistency
  "editor.wordWrap": "on", // Word wrap for better text management
  "editor.multiCursorModifier": "ctrlCmd", // Enable multi-cursor with Ctrl/Cmd
  "editor.quickSuggestions": {
    "comments": "on",
    "strings": "on",
    "other": "on"
  },
  "glassit.alpha": 150,
  "editor.formatOnSave": true,
  "security.allowedUNCHosts": ["wsl.localhost"],
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell"
    },
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
      ],
      "args": [],
      "icon": "terminal-cmd"
    },
    "Git Bash": {
      "source": "Git Bash"
    },
    "Ubuntu-24.04 (WSL)": {
      "path": "C:\\WINDOWS\\System32\\wsl.exe",
      "args": ["-d", "Ubuntu-24.04"]
    }
  },
  "terminal.integrated.defaultProfile.windows": "Ubuntu-24.04 (WSL)",
  "editor.formatOnPaste": true,
  "terminal.integrated.commandsToSkipShell": [""],
  "editor.find.cursorMoveOnType": false,
  "editor.find.loop": false,
  "workbench.iconTheme": "Monokai Pro (Filter Octagon) Icons",
  "editor.cursorSmoothCaretAnimation": "on" // Enable quick suggestions as you type
}

```
