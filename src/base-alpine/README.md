# 🏔️ ALPINE  

## Summary  
*A lightweight Alpine-based container with Git and common dev tools pre-installed.*  

| Metadata | Value |  
|----------|-------|  
| **Categories** | Core, Other |  
| **Image type** | Dockerfile |  
| **Published images** | `mcr.microsoft.com/devcontainers/base:alpine` |  
| **Available image variants** | alpine-3.22, alpine-3.21, alpine-3.20, alpine-3.19 ([full list](https://mcr.microsoft.com/v2/devcontainers/base/tags/list)) |  
| **Published image architecture(s)** | x86-64, aarch64/arm64 |  
| **Container host OS support** | Linux, macOS, Windows |  
| **Container OS** | Alpine Linux |  
| **Languages, platforms** | Any |  

See [history](history) for details on published image contents.  

---

## Use this image  

You can reference pre-built versions of `.devcontainer/Dockerfile` in two ways:  

1. **Via `image` property** in `.devcontainer/devcontainer.json`  
2. **By updating `FROM`** in your own `Dockerfile`  

Examples:  
- `mcr.microsoft.com/devcontainers/base:alpine` (latest)  
- `mcr.microsoft.com/devcontainers/base:alpine-3.22`  
- `mcr.microsoft.com/devcontainers/base:alpine-3.21`  
- `mcr.microsoft.com/devcontainers/base:alpine-3.20`  
- `mcr.microsoft.com/devcontainers/base:alpine-3.19`  

📖 Refer to the [Dockerfile guide](https://containers.dev/guide/dockerfile) for more details.  

---

## 🔄 Versioning  

You can control update frequency by pinning to a [semantic version](https://semver.org/):  

- `mcr.microsoft.com/devcontainers/base:0-alpine`  
- `mcr.microsoft.com/devcontainers/base:0.209-alpine`  
- `mcr.microsoft.com/devcontainers/base:0.209.0-alpine`  

See [history](history) for version contents and [available tags](https://mcr.microsoft.com/v2/devcontainers/base/tags/list).  

---

## ⚙️ Included Tools  

Beyond `git`, this image also includes:  
- `zsh` shell  
- [Oh My Zsh!](https://ohmyz.sh/) configuration framework  
- Non-root `vscode` user with `sudo` access  
- Common development dependencies  

---

## 📜 License  

Copyright (c) Microsoft Corporation.  
Licensed under the MIT License. See [LICENSE](https://github.com/devcontainers/images/blob/main/LICENSE).  

---

✨ This version makes the doc more scannable with icons, headings, and highlights. Do you want me to also add a **quick-start example** showing how to spin up a container with this Alpine base in VS Code?
