# Flatpak-updater
Flatpaks don't autoupdate without a GUI store. But using this systemd service they can easily do that. A nice message is displayed after the updates.

Install

```
wget https://github.com/trytomakeyouprivate/Flatpak-updater/raw/main/flatpak-automatic.service -p ~/.local/share/systemd/user/
wget https://github.com/trytomakeyouprivate/Flatpak-updater/raw/main/flatpak-automatic.timer -p ~/.local/share/systemd/user/

systemctl enable flatpak-automatic
```
