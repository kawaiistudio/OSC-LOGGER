# 💠 VRC OSC CONSOLE

An advanced monitoring and control interface for **VRChat** utilizing the **OSC** (Open Sound Control) protocol. This console provides real-time tracking of instance events, avatar changes, and direct interaction with the in-game chatbox.

---

## 🚀 Key Features

* **Real-Time Live Feed:** Monitor player `JOIN` and `LEFT` events instantly.
* **VRChat & VRCX Integration:** Direct hooks into `VRChat.log` and the `VRCX.sqlite3` database for comprehensive history.
* **Avatar Tracking:** Automatic detection of avatar swaps with full `usr_` and `avtr_` ID logging.
* **Multi-Account Support:** Quick switching between profiles (e.g., Kaichi Sama, Dr Mundo, Brior, etc.).
* **Integrated Chatbox:** Send text messages directly to the VRChat chatbox via the OSC interface.
* **Avatar Cache Monitoring:** Tracks assets being loaded locally by the client.

## 🛠️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/VRC-OSC-CONSOLE.git](https://github.com/your-username/VRC-OSC-CONSOLE.git)
    cd VRC-OSC-CONSOLE
    ```

2.  **Install Dependencies:**
    Make sure you have Python installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Enable OSC:**
    Ensure **OSC** is toggled to **ON** in your VRChat Action Menu or Settings.

4.  **Run the Console:**
    ```bash
    python server.py
    ```

## 📂 Data Sources Configuration

The console requires access to your local log and database files:

* **VRChat Logs:** `C:\Users\%USERNAME%\AppData\LocalLow\VRChat\VRChat`
* **VRCX Database:** `C:\Users\%USERNAME%\AppData\Roaming\VRCX\VRCX.sqlite3`

## 🖥️ UI Design & Visuals

The interface uses a "Cyberpunk Terminal" aesthetic for maximum immersion:
* **Green (#00FF41):** Connection status and active indicators.
* **Magenta:** Avatar-related events and updates.
* **Cyan:** System info, User IDs, and VRCX database logs.

---

> **Disclaimer:** This is a third-party tool designed for monitoring and is not affiliated with VRChat Inc.
