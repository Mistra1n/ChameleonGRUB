# ChameleonGRUB 🦎

A dynamic GRUB theme shuffler that gives your bootloader a fresh look every time you reboot!
You can add your themes if you download them


## ✨ Features
- **Random Theme Rotation**: New theme on every boot
- **Preview Mode**: Test themes without rebooting (`--preview`)
- **Theme Downloads**: Add new themes directly (`--download <URL>`)
- **Exclusion List**: Block themes you dislike (`exclude.conf`)
- **30+ Built-in Themes**: From sleek to artistic

## 🛠 Installation
```bash
git clone https://github.com/mistra1n/ChameleonGRUB.git
cd ChameleonGRUB
sudo ./install.sh
```
Verify Permissions:
Ensure scripts are executable:
```
chmod +x install.sh uninstall.sh ChameleonGRUB
```
## 🎮 Usage

```python
Command	                                  Description
:-------------------- |                | ----------------: |

sudo ChameleonGRUB	                      Apply random theme

sudo ChameleonGRUB --preview	              Preview next theme

sudo ChameleonGRUB --list	              Show available themes

sudo ChameleonGRUB --download
https://gnome-look.org/123	              Install new theme

sudo ./uninstall.sh	                      Remove ChameleonGRUB
```

## 📸 Theme Gallery
Cyberpunk	Tux	Minimal

## ⚙️ Configuration

Edit /etc/ChameleonGRUB/exclude.conf to block themes:
```python
# Example:
cyberpunk
tux
```
## 📜 License
This project is licensed under the **GNU GPLv3**.  
See [LICENSE](LICENSE) for full terms.

#Linux #GRUB #OpenSource #KaliLinux
