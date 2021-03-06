# Chat w/ @aubreypwd

![image](https://user-images.githubusercontent.com/1753298/126911319-6641501f-57f9-4970-a4a6-5902ae4074e7.png)

An native MacOS App for tlk.io/aubreypwd where you can chat with me. I mostly use this app for people that link to my tlk.io to chat with them, but you can technically download it and use it.

# Install

## Homebrew Cask

### Install

```bash
brew tap aubreypwd/homebrew-cask
brew update
brew cask install chat-with-aubreypwd
```

### Upgrade

```
brew update
brew upgrade chat-with-aubreypwd
```

## Download

Or download the `.dmg` in [releases](https://github.com/aubreypwd/chat-with-aubreypwd-mac/releases/latest) and install per usual.

*_Note, you will have to Right-click on the tlk.io/aubreypwd to open for the first time._*

---

# Development

1. Clone repo
2. `npm install`
3. `npm run build`

`npm run build` will built the application to `build/` and  `npm run dist` to generate a `.dmg` in `dist/` for distribution and installation.
