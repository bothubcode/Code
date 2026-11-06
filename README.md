# BotHub Code

The AI coding agent on [BotHub](https://bothub.chat) models, in your terminal and on your desktop.

This repository publishes the builds. Download them from [Releases](https://github.com/bothubcode/Code/releases).

## Install in the terminal

```bash
# macOS and Linux
curl -fsSL https://github.com/bothubcode/Code/releases/latest/download/install | bash

# npm, Yarn or Bun, on any system
npm install --global bothub-code
yarn global add bothub-code
bun add --global --trust bothub-code

# Homebrew
brew install bothubcode/tap/bothub-code

# Arch Linux
paru -S bothub-code-bin
yay -S bothub-code-bin
```

Then run `bothub-code` and connect your BotHub API key. Create a key at
[bothub.chat/profile/for-developers](https://bothub.chat/profile/for-developers).

`bothub-code upgrade` updates a copy installed any of these ways, except from the AUR, where your helper does it.

## Desktop app

Download the installer for your system from the
[latest release](https://github.com/bothubcode/Code/releases/latest). The app updates itself.

## Links

- [BotHub API documentation](https://bothub.chat/api/documentation)
- [Support](https://t.me/BotHub_Tech_Support_bot)
