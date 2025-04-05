# npm and TypeScript Setup Guide for macOS

Follow these steps to install Node.js (which includes npm) and the TypeScript compiler on macOS.

**Method 1: Using the Official Installer**

1.  **Download Node.js:**
    * Go to the official Node.js website: [https://nodejs.org/](https://nodejs.org/)
    * Download the **LTS (Long-Term Support)** version.
    * **Command to open the website (optional, run in Terminal):**
        ```bash
        open [https://nodejs.org/](https://nodejs.org/)
        ```

2.  **Install Node.js:**
    * Run the downloaded `.pkg` installer and follow the on-screen instructions.

3.  **Verify Node.js and npm Installation:**
    * Open **Terminal** (search for "Terminal" in Spotlight or find it in /Applications/Utilities/).
    * Run the following commands to check the installed versions:
        ```bash
        node -v
        ```
        **Expected Output:** A version number (e.g., `v18.16.0`)

        ```bash
        npm -v
        ```
        **Expected Output:** A version number (e.g., `9.5.1`)

**Method 2: Using Homebrew (Recommended)**

1.  **Install Homebrew (if you don't have it):**
    * Open **Terminal** and run:
        ```bash
        /bin/bash -c "$(curl -fsSL [https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh](https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh))"
        ```
        Follow the prompts to install Homebrew.

2.  **Install Node.js:**
    * In **Terminal**, run:
        ```bash
        brew update
        brew install node
        ```

3.  **Verify Node.js and npm Installation:**
    * In **Terminal**, run:
        ```bash
        node -v
        ```
        **Expected Output:** A version number (e.g., `v18.16.0`)

        ```bash
        npm -v
        ```
        **Expected Output:** A version number (e.g., `9.5.1`)

**Install TypeScript Compiler (for both methods):**

1.  Open **Terminal** and run the following command to install TypeScript globally:
    ```bash
    npm install -g typescript
    ```

2.  **Verify TypeScript Installation:**
    * Run the following command to check the installed version of the TypeScript compiler:
        ```bash
        tsc -v
        ```
        **Expected Output:** A version number (e.g., `Version 5.0.4`)

Now you have npm and the TypeScript compiler installed on your macOS system.
