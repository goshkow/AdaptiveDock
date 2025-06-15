# AdaptiveDock

A macOS utility for making your Dock adaptive and intelligent.
[Watch the AdaptiveDock demo video on YouTube](https://youtu.be/OK3HIASEuEk)

## Features

- Auto-hide Dock when space is limited  
- Show Dock only when there is enough free space  
- Customizable activation size  
- Background process without Dock icon  
- Autostart on login option  

## 🧩 Installation

1. **Download** the latest release `.dmg` file from the [Releases](https://github.com/goshkow/AdaptiveDock/releases) section.  
2. **Open** the `.dmg` file and **drag** `AdaptiveDock.app` to your **Applications** folder.  
3. **Launch** the app from your Applications folder.

> **Note:** The source code is not publicly available. Only the compiled releases are provided.

---

### ⚠️ Important Notice for macOS Security

If macOS shows a warning like "The application is damaged and can't be opened" or "Cannot verify developer," you can remove the quarantine attribute using the Terminal:

```bash
sudo xattr -r -d com.apple.quarantine /Applications/AdaptiveDock.app
```

## Supported macOS Versions

AdaptiveDock supports macOS 11 Big Sur and newer.

## Author

goshkow — [goshkowdigital.ru](https://goshkowdigital.ru)

## License

This project is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0).  
You are free to share and use the releases but not allowed to modify the source code or binaries.

For more information, see the [LICENSE](./LICENSE) file or visit:  
https://creativecommons.org/licenses/by-nd/4.0/
