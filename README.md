# Homebrew Tap for PasteFence

This is the official Homebrew tap for [PasteFence](https://github.com/choru-k/PasteFence), a macOS menu bar app that masks sensitive information in clipboard text using local LLM inference.

## Installation

```bash
brew tap choru-k/pastefence
brew install --cask pastefence
```

## What is PasteFence?

PasteFence automatically detects and masks sensitive information (PII) before you paste text. All processing happens locally using MLX-Swift - your data never leaves your machine.

**Features:**
- Local LLM processing (no external API calls)
- Hybrid detection: fast regex + context-aware LLM
- Preview & approval before pasting
- Customizable hotkeys and masking formats

**Requirements:**
- macOS 14.0+ (Sonoma)
- Apple Silicon recommended

## Updates

When a new version is released:
```bash
brew upgrade --cask pastefence
```

## Uninstall

```bash
brew uninstall --cask pastefence
```

## Links

- [PasteFence Repository](https://github.com/choru-k/PasteFence)
- [Releases](https://github.com/choru-k/PasteFence/releases)
- [Issues](https://github.com/choru-k/PasteFence/issues)
