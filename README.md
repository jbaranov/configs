# OS Configuration

## macOS

1. Hide menu bar
```bash
defaults write -g _HIHideMenuBar -bool true
defaults write -g AppleMenuBarVisibleInFullscreen -bool false
defaults write com.apple.spaces spans-displays -bool true
```
Requires full logout to apply changes
