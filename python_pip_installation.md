### Installing Python and Required Runtimes

1. **Download Python**:
   - Visit the [Python website](https://www.python.org/downloads/) to download the latest version of Python.
   - Choose the appropriate installer for your operating system (Windows, macOS, or Linux).

2. **Install Python**:
   - **Windows**: Run the downloaded Python installer (.exe file). Make sure to check the box that says "Add Python to PATH" during installation.
   - **macOS**: Open the downloaded Python installer (.pkg file) and follow the installation prompts.
   - **Linux**: Use your package manager to install Python. For example, on Debian/Ubuntu, run `sudo apt-get install python3`.

3. **Verify Installation**:
   - Open a terminal or command prompt.
   - Type `python --version` or `python3 --version` and press Enter. You should see the installed Python version displayed.

4. **Install Additional Tools**:
   - **pip**: Python's package manager, `pip`, usually comes installed with Python. You can verify its installation by typing `pip --version` in the terminal.



5. **Test Your Installation**:
   - Open a new terminal or command prompt.
   - Type `python` or `python3` and press Enter to enter the Python interpreter.
   - You should see the Python prompt (`>>>`), indicating that Python is installed and running correctly.
   - Type `exit()` and press Enter to exit the Python interpreter.

Troubleshooting:
* If Python is not recognized, ensure it is added to the system PATH.
* Upgrade pip if installation issues occur:
   ```bash
    python -m pip install --upgrade pip
     ```