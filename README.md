# ReVive OS

**Rescue. Repair. Recover.**

ReVive OS is a lightweight, bootable Linux distro built for **fixing broken computers**. It runs directly from a USB drive or Live CD — no installation needed. Just plug it in, boot it, and start repairing.

Built on **Debian 12 (Bookworm)** with the **XFCE** desktop, ReVive OS works on both old and new computers (BIOS and UEFI).

---

## 🎯 What Can ReVive OS Do?

- 🔓 **Unlock Windows accounts** — reset forgotten passwords
- 📁 **Recover your files** — from corrupted or unbootable Windows/Linux/macOS systems
- 💽 **Fix partitions** — resize, repair, or rebuild damaged partitions
- 🔍 **Recover deleted files** — photos, documents, videos, and more
- 🔐 **Mount encrypted drives** — BitLocker (Windows), LUKS (Linux), VeraCrypt
- 🍎 **Access macOS drives** — read APFS and HFS+ partitions
- 📦 **Clone or back up entire disks** — even damaged ones
- 🌐 **Browse the internet** — download drivers, look up fixes, or get help
- 🖥️ **View hardware info** — identify the exact problem before fixing it

Everything comes **preinstalled**. No setup, no internet required for the core tools.

---

## 💻 Supported File Systems

| Family | File Systems |
|--------|--------------|
| **Windows** | NTFS, FAT, exFAT, BitLocker |
| **Linux** | ext2/3/4, Btrfs, XFS, ReiserFS, LUKS |
| **macOS** | APFS (read-only), HFS/HFS+ |
| **Other** | VeraCrypt volumes |

---

## 🖥️ System Requirements

- **CPU:** 64-bit (x86_64 / amd64)
- **RAM:** 2 GB minimum (4 GB recommended)
- **USB drive:** 4 GB or larger
- **Boot:** Works on **both BIOS (legacy) and UEFI** systems

Runs comfortably on computers from ~2008 onwards.

---

## 🚀 How to Use

1. **Download the ISO** from the link below.
[Download]([https://github.com](https://drive.google.com/file/d/1kJHS9XctNtCx8gWl6L-M1DKbXyRW60JK/view?usp=sharing))
2. **Write it to a USB drive** using one of these tools:
   - [Rufus](https://rufus.ie/) (Windows)
   - [Balena Etcher](https://etcher.balena.io/) (Windows / macOS / Linux)
   - `dd` command (Linux):
     ```bash
     sudo dd if=revive-os.iso of=/dev/sdX bs=4M status=progress && sync
