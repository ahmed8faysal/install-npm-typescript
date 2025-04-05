# npm and TypeScript Setup Guide for Windows

Follow these steps to install Node.js (which includes npm) and the TypeScript compiler on Windows.

1.  **Download Node.js:**
    * Go to the official Node.js website: [https://nodejs.org/](https://nodejs.org/)
    * Download the **LTS (Long-Term Support)** version.
    * **Command to open the website (optional, run in Command Prompt or PowerShell):**
        ```bash
        start [https://nodejs.org/](https://nodejs.org/)
        ```

2.  **Install Node.js:**
    * Run the downloaded `.msi` installer.
    * Follow the on-screen instructions. The installer will typically include npm.

3.  **Verify Node.js and npm Installation:**
    * Open **Command Prompt** (search for "cmd" in the Start Menu) or **PowerShell** (search for "powershell").
    * Run the following commands to check the installed versions:
        ```bash
        node -v
        ```
        **Expected Output:** A version number (e.g., `v18.16.0`)

        ```bash
        npm -v
        ```
        **Expected Output:** A version number (e.g., `9.5.1`)

4.  **Install TypeScript Compiler:**
    * In the same **Command Prompt** or **PowerShell** window, run the following command to install TypeScript globally:
        ```bash
        npm install -g typescript
        ```
        This command downloads and installs the TypeScript compiler so you can use it from any project.

5.  **Verify TypeScript Installation:**
    * Run the following command to check the installed version of the TypeScript compiler:
        ```bash
        tsc -v
        ```
        **Expected Output:** A version number (e.g., `Version 5.0.4`)

Now you have npm and the TypeScript compiler installed on your Windows system.
