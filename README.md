#  Zorin OS Installation Guide

This repository provides a step-by-step guide for installing **Zorin OS**, either alongside your current operating system or as a standalone OS.

---

##  What You'll Need

- A computer that meets [Zorin OS system requirements](https://zorin.com/os/download/)
- A USB flash drive:
  - **Core / Lite**: ≥ 4 GB
  - **Pro / Education**: ≥ 8 GB
- (Optional) An external drive or cloud storage to back up important files
- Zorin OS `.iso` file from [zorin.com](https://zorin.com/os/download/)
- A USB flashing tool (e.g. [balenaEtcher](https://www.balena.io/etcher/))

---

##  Step 1: Download Zorin OS

1. Visit the [Zorin OS download page](https://zorin.com/os/download/)
2. Select your preferred edition and download the `.iso` file
3. Save the file in your **Downloads** folder

---

##  Step 2: Back Up Your Data (Optional)

- Back up important files to an external drive or cloud storage
- Installing a new OS can overwrite your current data

---

##  Step 3: Create a Bootable USB Drive

1. Download and install [balenaEtcher](https://www.balena.io/etcher/)
2. Plug in your USB flash drive
3. Launch **balenaEtcher**
4. Click `Flash from file` and select the Zorin OS `.iso`  
   ![Flash from file](https://help.zorin.com/docs/getting-started/install-zorin-os/balenaEtcher-1.png)
5. Click `Select target` and choose your USB drive  
   ![Select USB target](https://help.zorin.com/docs/getting-started/install-zorin-os/balenaEtcher-3.png)
6. Click `Flash!` to begin writing the OS to your USB drive

> ⚠️ **Note**: All contents of the USB drive will be erased.

---

##  Step 4: Boot from USB

1. Power off the computer where you want to install Zorin OS
2. Plug in the USB Install Drive
3. Power it on and immediately press the boot menu key:
   - Common keys: `Esc`, `F2`, `F12`, `Delete`, or `Option (Mac)`
4. Select the USB device from the boot menu
5. Choose **"Try or Install Zorin OS"** from the boot menu

> If using an NVIDIA GPU (after 2013), select the NVIDIA option.

---

## 🖱️ Step 5: Install Zorin OS

1. Once booted into Zorin OS, click **"Install Zorin OS"**
   ![Welcome Menu](https://help.zorin.com/docs/getting-started/install-zorin-os/welcome-menu.png)
2. Follow the on-screen instructions:
   - Connect to Wi-Fi (recommended)
   - Choose your **installation type**:
     - `"Install Zorin OS alongside [your OS]"` (dual-boot)
     - `"Erase disk and install Zorin OS"` (clean install)
     - `"Something else"` (manual partitioning for advanced users)
3. Continue setup: location, keyboard, username, password
4. Click `Install Now` and wait for it to finish
5. Restart your computer when prompted
   ![Installer](https://help.zorin.com/docs/getting-started/install-zorin-os/installer.png)

---

##  Optional: Reuse Your USB Drive

To reuse the USB flash drive after installation:

- On **Windows**: use **Rufus** or Disk Management
- On **Linux/macOS**: use **Disk Utility** or `GParted`

---

##  Resources

-  [Zorin OS Official Website](https://zorin.com/)
-  [balenaEtcher USB Tool](https://www.balena.io/etcher/)
-  [Zorin OS Help & Documentation](https://zorin.com/help/)
-  [Manual Partitioning Guide](https://help.zorin.com/docs/getting-started/install-zorin-os/manual-partitioning/)

---

##  License

This guide is provided as-is and free to use. 

---

**for Linux beginners to confidently install Zorin OS**
