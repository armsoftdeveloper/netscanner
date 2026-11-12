# NetScanner

A fast local network scanner for Windows and Linux, made for network engineers and system administrators.

NetScanner finds every device on your network — including devices that do not answer ping — and shows
what each one is: name, IP and MAC address, vendor, device type, operating system and open services.

## Download

| System | File | |
|---|---|---|
| **Windows 10 / 11** (64-bit) | [NetScanner-Setup.msi](https://github.com/armsoftdeveloper/netscanner/raw/main/NetScanner-Setup.msi) | about 49 MB |
| **Ubuntu, Debian, Linux Mint** | [NetScanner-Linux.deb](https://github.com/armsoftdeveloper/netscanner/raw/main/NetScanner-Linux.deb) | about 34 MB |
| **Any Linux** (Fedora, Arch, openSUSE…) | [NetScanner-Linux.AppImage](https://github.com/armsoftdeveloper/netscanner/raw/main/NetScanner-Linux.AppImage) | about 40 MB |

Nothing else needs to be installed.

## Installation

**Windows**

1. Run `NetScanner-Setup.msi`.
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
3. Start NetScanner from the Start menu or the desktop shortcut.

The Windows version checks for new versions by itself and offers to install them.

**Ubuntu / Debian / Linux Mint**

```bash
sudo apt install ./NetScanner-Linux.deb
```

Then start **NetScanner** from the applications menu, or run `netscanner` in a terminal.

**Any Linux (AppImage)**

```bash
chmod +x NetScanner-Linux.AppImage
./NetScanner-Linux.AppImage
```

If it does not start, install FUSE 2 (`libfuse2` or `libfuse2t64` on Ubuntu 24.04).

## Features

- Scans a whole subnet in seconds and shows results live
- Detects device type and OS: PCs, servers, routers, switches, printers, cameras, NAS, phones, TVs
- Open ports and services, with one-click Web, RDP, SSH and shared folder access
- Highlights new, missing and changed devices since the previous scan
- Network map with switch ports (SNMP, LLDP/CDP)
- Ping monitor with live graphs: latency, jitter and packet loss for several hosts (Windows)
- Built-in network tools: traceroute, DNS lookup, whois, SSL certificate check, subnet calculator, MAC lookup (Windows)
- Wake-on-LAN
- Export to Excel (CSV), HTML report or JSON
- 30 interface languages, light and dark themes
- Command-line version `netscan` included

---

Developed in Armenia by **Armen Vardanyan**
