# SCBooster ( High Risk )

A Python-based automation tool to boost your Snapchat score by automatically sending multiple snaps to your contacts.

## Features

- **Automated Snap Sending**: Automates the process of sending 7 snaps per cycle to selected contacts.
- **Multi-Snap Functionality**: Leverages Snapchat's "Multi Snap" feature for rapid score boosting.
- **Custom Position Setup**: Interactive setup to configure screen positions for different Snapchat UI elements.
- **Real-time Statistics**: Tracks sent snaps and elapsed time in the console title.
- **Shortcut Integration**: Works with your existing Snapchat shortcuts for bulk sending.
- **Emergency Stop**: Press `F4` to stop the process at any time.

## Requirements

- **Windows OS** (Due to `ctypes.windll` usage)
- **Python 3.6+**
- **Any android emulator ( LDPlayer ) Recommended**
- **Active internet connection**

## Installation

1. **Install Python** (if not already installed):

    ```bash
    python get-pip.py
    ```

2. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

    **Required Python Packages** (automatically installed via `requirements.txt`):
    - `colorama`: For colored console output
    - `pyautogui`: For screen interaction automation
    - `keyboard`: For keyboard input detection

## Usage

1. **Start the application**:

    ```bash
    python SCBooster.py
    ```

2. **Setup Process**:
    - Follow on-screen instructions to configure screen positions for:
        - Camera button
        - Take picture button
        - Arrow down button
        - Multi Snap button
        - Edit & Send button
        - Send To button
        - Your shortcut
        - Select all button
        - Send snap button

3. **Enter shortcut member count**:
    - Input the number of people in your selected shortcut when prompted.

4. **Position Preparation**:
    - Navigate to your Snapchat chats window.
    - Press `F` when ready to start sending.

5. **Operation**:
    - The tool will automatically:
        - Switch to camera mode
        - Take 7 snaps
        - Edit and send to your shortcut
        - Repeat every 4 seconds
    - Real-time statistics shown in console title:
        - Total sent snaps
        - Elapsed time
        - Estimated score increase

6. **Emergency Stop**:
    - Press `F4` at any time to stop the process.

## Important Notes

- Keep Snapchat window visible and undisturbed during operation.
- Ensure good internet connection for smooth operation.
- The score increase rate depends on your shortcut size (snaps sent = 7 × number of people in shortcut).
- Snapchat may detect automated activity - use at your own risk.
- Recommended maximum runtime: 1-2 hours per session.

## Compliance Notice
Using automated tools with Snapchat may violate their terms of service. im not for any account restrictions or consequences resulting from use of this software.
