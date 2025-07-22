
# 🖥️ Zorin OS Installation Guide

This repository provides a step-by-step guide for installing **Zorin OS**, either alongside your current operating system or as a standalone OS.

---

## ✅ What You'll Need

- A computer that meets [Zorin OS system requirements](https://zorin.com/os/download/)
- A USB flash drive:
  - Core / Lite: **≥ 4 GB**
  - Pro / Education: **≥ 8 GB**
- (Optional) An external drive or cloud storage to back up important files
- Zorin OS `.iso` file (download from [zorin.com](https://zorin.com/os/download/))
- A USB flashing tool (e.g. [balenaEtcher](https://www.balena.io/etcher/))

---

## 📥 Step 1: Download Zorin OS

1. Visit the [official Zorin OS download page](https://zorin.com/os/download/)
2. Select your preferred edition and download the `.iso` file
3. Save it in your **Downloads** folder

![Download Zorin OS](https://zorin.com/static/download-hero-core-2-6e229e9958ff.svg)

---

## 💾 Step 2: Back Up Your Data (Optional)

- Back up important files to an external drive or cloud storage
- Installing a new OS can overwrite your current data

![Back Up Files](https://images.unsplash.com/photo-1607746882042-944635dfe10e?fit=crop&w=800&q=80)

---

## 🔧 Step 3: Create a Bootable USB Install Drive

1. Download [balenaEtcher](https://www.balena.io/etcher/)
2. Plug in your USB flash drive
3. Open **balenaEtcher**
4. Select the Zorin OS `.iso` file  
5. Choose your USB drive as the target  
6. Click **"Flash!"**

![balenaEtcher Interface](https://raw.githubusercontent.com/balena-io/etcher/master/assets/img/screenshots/etcher.png)

> **Note:** This will erase all data on the USB flash drive.

---

## 🚀 Step 4: Boot from the USB Drive

1. Shut down the computer where you’ll install Zorin OS
2. Plug in the USB Install Drive
3. Power it on and immediately press the boot key:
   - Common keys: `Esc`, `F2`, `F12`, `Delete`, `Option (Mac)`
4. Select your USB device from the boot menu
5. Choose **"Try or Install Zorin OS"**

![Boot Menu Example](https://linuxhint.com/wp-content/uploads/2020/09/Figure-1-Boot-from-USB.png)

> If you have an NVIDIA GPU, select the option with **modern NVIDIA drivers**.

---

## 🖱️ Step 5: Install Zorin OS

1. After booting into Zorin OS, click **"Install Zorin OS"**

![Zorin OS Desktop](https://zorin.com/static/os-16-desktop-7d469e16feeb.png)

2. Follow the on-screen instructions:
   - Connect to Wi-Fi
   - Choose installation type:
     - **Dual-boot**: "Install Zorin OS alongside [existing OS]"
     - **Erase all**: "Erase disk and install Zorin OS"
     - **Manual**: For advanced partitioning

![Zorin OS Installer](https://www.linuxtechi.com/wp-content/uploads/2021/08/zorin-os-16-install-type.png)

3. Complete the setup steps (location, keyboard layout, username, password)
4. Click **"Install Now"** and wait for installation to finish
5. Restart the computer when prompted

---

## 🎉 Post-Installation

- Remove the USB drive after restart
- Boot into your newly installed Zorin OS
- Enjoy your Linux-powered experience!

![Welcome to Zorin OS](https://zorin.com/static/welcome-1-155ddce50c68.png)

---

## 🔄 Optional: Reuse Your USB Flash Drive

To reuse your USB flash drive, simply format it using:
- **Disk Utility** (Linux/macOS)
- **Rufus** or **Disk Management** (Windows)

---

## 🔗 Resources

- [Zorin OS Official Site](https://zorin.com/)
- [balenaEtcher](https://www.balena.io/etcher/)
- [Zorin OS Help & Support](https://zorin.com/help/)

---

## 💬 License

This guide is open and free to use. Attribution appreciated.

---

**Made with ❤️ for Linux beginners and switchers.**
