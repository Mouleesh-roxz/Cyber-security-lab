# Cyber-security-lab
Here's a sample `README.md` file that you can use on GitHub to explain how to install Linux on Windows using VirtualBox:

---

# 🐧 Install Linux on Windows using VirtualBox

This guide will walk you through installing a Linux distribution (such as Ubuntu) on a Windows machine using [Oracle VM VirtualBox](https://www.virtualbox.org/). This is ideal for development, testing, or learning Linux without affecting your main system.

---

## 📋 Prerequisites

* A Windows PC (Windows 10/11 recommended)
* Minimum 4 GB RAM (8 GB or more recommended)
* At least 20 GB of free disk space
* Internet connection

---

## 🧰 Required Downloads

1. **VirtualBox** – [Download Here](https://www.virtualbox.org/wiki/Downloads)
2. **Linux ISO file** (e.g. Ubuntu, Debian, Fedora):

   * Ubuntu: [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)
   * Fedora: [https://getfedora.org/](https://getfedora.org/)
   * Debian: [https://www.debian.org/distrib/](https://www.debian.org/distrib/)

---

## 🛠 Installation Steps

### 1. Install VirtualBox

* Download and run the VirtualBox installer.
* Follow the setup wizard (you can leave most options as default).
* Finish installation and launch VirtualBox.

### 2. Download a Linux ISO

* Choose a Linux distribution.
* Download the `.iso` file from the official website.

### 3. Create a New Virtual Machine

* Open VirtualBox.
* Click **"New"**.
* Enter a name (e.g., Ubuntu), select **"Linux"** and version (e.g., "Ubuntu (64-bit)").
* Allocate memory (at least 2048 MB for Ubuntu).
* Create a virtual hard disk (at least 20 GB, dynamically allocated recommended).

### 4. Mount the ISO File

* Select your VM and click **"Settings"** → **"Storage"**.
* Under **Controller: IDE**, click **Empty**, then click the disk icon on the right.
* Choose **"Choose a disk file…"** and select the downloaded ISO.

### 5. Start the Virtual Machine

* Click **"Start"**.
* The VM will boot using the ISO.
* Follow the Linux installation steps (select language, timezone, partitioning, etc.).

### 6. Remove ISO after Installation

* After installing Linux and rebooting, go to **Settings** → **Storage** and remove the ISO from the optical drive.

---

## 🧪 Test Your Linux VM

* Boot your VM.
* Login and test features like terminal access, file manager, and system settings.
* You now have a full Linux environment running on Windows!

---

## 🚀 Optional: Install Guest Additions

To enable full screen, clipboard sharing, and better performance:

1. Start your Linux VM.
2. From VirtualBox menu: **Devices > Insert Guest Additions CD Image**.
3. Run the installer inside your Linux system (may require terminal access and superuser privileges).

---

## 📷 Screenshots (Optional)

Add screenshots of:

* VirtualBox setup
* ISO download
* Linux installation steps
* Final working desktop

---

## 📚 Resources

* [Official VirtualBox Documentation](https://www.virtualbox.org/manual/)
* [Ubuntu Installation Guide](https://ubuntu.com/tutorials/install-ubuntu-desktop)

---

## 📌 License

This project is licensed under the MIT License.

---

Let me know if you'd like this customized for a specific Linux distribution like **Ubuntu**, or want to include screenshots or shell commands.
