### Steps to Install Docker

**For Windows:**

1. **Download Docker Desktop:**
   - Visit the [Docker Desktop download page](https://www.docker.com/products/docker-desktop).
   - Click on "Download for Windows".

2. **Install Docker Desktop:**
   - Open the downloaded installer and run it.
   - Follow the on-screen installation instructions.
   - When prompted, ensure the boxes for "Install required Windows components for WSL 2" and "Add shortcuts to desktop" are checked.

3. **Start Docker Desktop:**
   - Once installed, launch Docker Desktop from the Start menu or desktop shortcut.
   - Docker will start, and you should see the Docker whale icon in the system tray.

4. **Enable WSL 2 (if not already enabled):**
   - Open PowerShell as Administrator and run:
     ```shell
     wsl --install
     ```
   - Restart your computer if prompted.

5. **Verify Installation:**
   - Open PowerShell or Command Prompt and run:
     ```shell
     docker --version
     ```
   - This should display the Docker version, indicating a successful installation.

Troubleshooting:
* Ensure virtualization is enabled in BIOS/UEFI settings if Docker fails to start.