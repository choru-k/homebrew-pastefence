<div align="center">

<!-- Hero Image - Add your screenshot here -->
<img src="assets/hero.png" alt="PasteFence Preview" width="600">

# PasteFence

**Mask sensitive information before pasting. All processing stays on your Mac.**

[![Version](https://img.shields.io/badge/version-1.0.4-blue.svg)](https://github.com/choru-k/PasteFence/releases)
[![macOS](https://img.shields.io/badge/macOS-14.0+-000000.svg?logo=apple)](https://github.com/choru-k/PasteFence)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/choru-k/PasteFence/blob/main/LICENSE)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-optimized-orange.svg)](https://github.com/choru-k/PasteFence)

[**Install**](#-quick-install) ·
[**Demo**](#-how-it-works) ·
[**Main Repo**](https://github.com/choru-k/PasteFence)

</div>

---

## Quick Install

```bash
brew tap choru-k/pastefence
brew install --cask pastefence
```

That's it! PasteFence will appear in your menu bar.

---

## How It Works

<div align="center">

<img src="assets/hero.png" alt="PasteFence Preview" width="700">

</div>

| Step | Action | Description |
|:---:|:---|:---|
| **1** | Copy text normally | `Cmd + C` |
| **2** | Trigger masking | `Cmd + Shift + V` |
| **3** | Review detected PII | Preview window shows what will be masked |
| **4** | Approve & paste | Masked text goes to clipboard and pastes |

---

## Features

<table>
<tr>
<td width="50%">

### 🔒 100% Local Processing
All detection happens on-device using MLX-Swift. Your sensitive data never leaves your Mac.

</td>
<td width="50%">

### ⚡ Hybrid Detection
Fast regex catches common patterns (~1ms), while local LLM handles context-aware detection.

</td>
</tr>
<tr>
<td width="50%">

### 👁️ Preview Before Paste
Review exactly what will be masked. Toggle individual items on/off before approving.

</td>
<td width="50%">

### 🎨 Customizable
Choose masking formats, configure hotkeys, and adjust detection sensitivity.

</td>
</tr>
</table>

---

## What It Detects

- 📧 Email addresses
- 📱 Phone numbers (international formats)
- 💳 Credit card numbers
- 🔑 API keys (OpenAI, GitHub, AWS, Slack)
- 🎫 JWT tokens
- 🌐 IP addresses
- 🔐 Passwords & private keys
- 🆔 Korean resident registration numbers

---

## Screenshots

<div align="center">

| Preview Window | Settings |
|:---:|:---:|
| <img src="assets/preview.png" width="350"> | <img src="assets/settings.png" width="350"> |

</div>

---

## Requirements

| Requirement | Details |
|:---|:---|
| **macOS** | 14.0+ (Sonoma or later) |
| **Chip** | Apple Silicon recommended |
| **RAM** | 8GB minimum |
| **Permissions** | Accessibility (for hotkeys) |

---

## Commands

```bash
# Update to latest version
brew upgrade --cask pastefence

# Uninstall
brew uninstall --cask pastefence
```

---

## Links

- 📦 [Main Repository](https://github.com/choru-k/PasteFence)
- 🚀 [Releases](https://github.com/choru-k/PasteFence/releases)
- 🐛 [Report Issues](https://github.com/choru-k/PasteFence/issues)

---

<div align="center">

**Made with ❤️ for privacy-conscious Mac users**

</div>
