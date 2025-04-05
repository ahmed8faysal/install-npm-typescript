# npm and TypeScript Setup Guide for Linux

Follow these steps to install Node.js (which includes npm) and the TypeScript compiler on Linux. The specific commands might vary slightly depending on your distribution.

**General Steps (using package managers):**

1.  **Update Package Lists:**
    * **Debian/Ubuntu:**
        ```bash
        sudo apt update
        ```
    * **Fedora/CentOS/RHEL:**
        ```bash
        sudo dnf update
        # or
        sudo yum update
        ```
    * **Arch Linux:**
        ```bash
        sudo pacman -Syu
        ```

2.  **Install Node.js and npm:**
    * **Debian/Ubuntu (Recommended - using NodeSource):**
        ```bash
        curl -sL [https://deb.nodesource.com/setup_lts.x](https://deb.nodesource.com/setup_lts.x) | sudo -E bash -
        sudo apt-get install -y nodejs
        ```
        (Replace `lts.x` with the desired LTS version, e.g., `setup_20.x`)
    * **Debian/Ubuntu (Alternative):**
        ```bash
        sudo apt install nodejs npm
        ```
        (You might need `sudo apt install nodejs-legacy` as well)
    * **Fedora/CentOS/RHEL:**
        ```bash
        sudo dnf install nodejs npm
        # or
        sudo yum install nodejs npm
        ```
    * **Arch Linux:**
        ```bash
        sudo pacman -S node npm
        ```

3.  **Verify Node.js and npm Installation:**
    * Open your **Terminal**.
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
    * In the same **Terminal** window, run the following command to install TypeScript globally:
        ```bash
        npm install -g typescript
        ```

5.  **Verify TypeScript Installation:**
    * Run the following command to check the installed version of the TypeScript compiler:
        ```bash
        tsc -v
        ```
        **Expected Output:** A version number (e.g., `Version 5.0.4`)

Now you have npm and the TypeScript compiler installed on your Linux system. Remember to adjust the installation commands based on your specific Linux distribution.
