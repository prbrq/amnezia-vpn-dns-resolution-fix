# Fix for the AmneziaVPN DNS Resolution Error on Linux

Fix is aimed at distributions based on `Arch` (`Manjaro`, `EndeavourOS`, `CachyOS`, `Arch` itself).

# How to Use

1) Download script file `wget https://raw.githubusercontent.com/prbrq/amnezia-vpn-dns-resolution-fix/refs/heads/main/amneziavpndnsresolutionfix`.
2) Make it executable chmod +x amneziavpndnsresolutionfix.
3) Run it: ./amneziavpndnsresolutionfix

Or just execute:

```sh
sudo pacman -S systemd-resolvconf
systemctl enable systemd-resolved
```

And then restart your computer.