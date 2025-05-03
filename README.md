# Termux-Overview
Collection of sources to set up and use Linux inside a Termux proot environment.

## Nützliches
- Skripte und Hinweise, um eine Termux PRoot Umgebung aufzusetzen (nicht ausprobiert); Problemlösung Audio mit X11 auf Samsung-Geräten; xRDP auf PRoot: [proot-distro-scripts](https://github.com/01101010110/proot-distro-scripts). xrdp-setup.sh in dieses Repo geklont.


## Optional xRDP Support --- For Ubuntu and Debian Environments Only!

Adds xRDP support, which allows you to connect to your environment remotely using a computer. 

**Copy and paste inside of your environment:**
```
curl -sL https://raw.githubusercontent.com/01101010110/proot-distro-scripts/main/xrdp-setup.sh -o xrdp-setup.sh && chmod +x xrdp-setup.sh && source xrdp-setup.sh
```
bzw. aus diesem Repo:
```
curl -sL https://raw.githubusercontent.com/vexplained/Termux-Overview/refs/heads/main/xrdp-setup-proot.sh -o xrdp-setup-proot.sh && chmod +x xrdp-setup-proot.sh && source xrdp-setup-proot.sh
```
