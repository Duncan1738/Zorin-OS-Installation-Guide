

##  Installation Steps

### 1.  Download Zorin OS

- Visit: [https://zorin.com/os/download/](https://zorin.com/os/download/)
- Choose **Zorin OS Core** (free), **Pro** (paid), or **Lite** (for low-end PCs)
- Download the `.iso` file

---

### 2.  Create a Bootable USB

#### 🔹 On Windows (Using Rufus)

1. Download [Rufus](https://rufus.ie/)
2. Insert an 8 GB+ USB stick
3. Open Rufus and select the `.iso` file
4. Click **Start** and choose “Write in ISO Image mode”

#### 🔹 On macOS or Linux (Using Etcher)

1. Download [balenaEtcher](https://www.balena.io/etcher/)
2. Select the `.iso` file, target USB, and click **Flash**

#### 🔹 On Linux (Using Terminal)

```python
sudo dd bs=4M if=zorin-os-*.iso of=/dev/sdX status=progress oflag=sync
⚠️ Replace /dev/sdX with your actual USB device (check with lsblk)
```
---

### 3. Boot from USB
1. Insert the USB into your PC
2. Restart your computer
3. Press the boot key (e.g., F2, F10, F12, DEL, or ESC) to open the Boot Menu
4. Select the USB drive to boot

---
### 4. Try or Install Zorin OS
1. Choose "Try Zorin OS" if you want to test before installing
2. Click "Install Zorin OS" to start the installation
3. Follow the wizard:
   - Choose language and keyboard layout
   - Select installation type:
         - Erase disk (fresh install)
         - Install alongside Windows (dual boot)
4. Set your timezone, username, and password
5. Click Install Now

---
### 5. Final Steps

1. Wait for installation to finish (~10–20 minutes)
2. Remove the USB when prompted
3. Reboot your PC
4. Log in and enjoy Zorin OS!

---
MIT licence
