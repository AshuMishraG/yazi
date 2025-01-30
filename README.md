# 🚀 Yazi - Blazing Fast Terminal File Manager

[Yazi](https://github.com/sxyazi/yazi) is a **minimalist**, **highly customizable**, and **blazing fast** terminal file manager written in Rust. It offers a smooth navigation experience with a modern UI.

---

## ✨ Features

- **Lightning-fast performance** with Rust.
- **Vim-like keybindings** for efficient navigation.
- **TUI-based modern interface** with preview support.
- **Asynchronous operations** for smooth file handling.
- **Highly customizable** via configuration files.
- **Extensible** with shell commands and scripts.

---

## 📥 Installation

### 🔧 Using Package Managers

#### 📦 Linux
sh
# Arch Linux
yay -S yazi

# Debian / Ubuntu
cargo install --git https://github.com/sxyazi/yazi.git


#### 🍎 macOS
sh
brew install yazi


#### 🖥️ Windows
sh
scoop install yazi


### 🛠 Manual Installation
If you prefer to build Yazi from source, ensure you have `cargo` installed, then run:

sh
cargo install --git https://github.com/sxyazi/yazi.git


---

## 🎮 Usage

### 📂 Open Yazi
sh
yazi


### 🔑 Keybindings

| Key        | Action                         |
|-----------|--------------------------------|
| `h`       | Go to parent directory         |
| `l`       | Enter directory / Open file    |
| `j`       | Move down                      |
| `k`       | Move up                        |
| `/`       | Search                         |
| `gg`      | Jump to top                    |
| `G`       | Jump to bottom                 |
| `q`       | Quit                           |

### 🛠 Customization
Yazi is highly customizable via configuration files. You can modify keybindings, themes, and behaviors by editing:

sh
~/.config/yazi/config.toml


---

## 📦 Plugins & Extensions
Yazi supports **custom scripts** and **external commands** for extended functionality. Check out the [official documentation](https://github.com/sxyazi/yazi/wiki) for more details.

---

## ⚡ Performance Tips
- Use **async mode** to handle large directories efficiently.
- Customize **preview commands** for file types in `~/.config/yazi/config.toml`.
- Enable **caching** to speed up navigation.

---

## 🛠 Troubleshooting

### 🚫 Yazi is not starting
Ensure it is installed correctly:
sh
which yazi
```
If it's not found, check your $PATH or reinstall using a package manager.

### ⚠️ Slow performance on large directories
- Try *disabling previews* in the configuration file.
- Make sure *async mode* is enabled.

---

## 📄 License
Yazi is open-source and licensed under the *MIT License*.

---

## 🌍 Resources & Links
- 📖 [Official GitHub Repository](https://github.com/sxyazi/yazi)
- 📚 [Yazi Wiki](https://github.com/sxyazi/yazi/wiki)
- 💬 [Discussions & Issues](https://github.com/sxyazi/yazi/issues)

---

## 📬 Contact
For suggestions, bug reports, or contributions, feel free to open an issue on GitHub or contribute via PRs! 🚀