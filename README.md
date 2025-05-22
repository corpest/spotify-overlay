# ATTENTION: I WILL PROBABLY NOT UPDATE OR FIX THIS FOR OTHER DISTROS UNLESS IT'S IN MY INTERESTS

# Spotify Overlay for Linux 🎵

A clean, transparent overlay widget for controlling Spotify playback — designed for Parrot OS and other Linux distros.

---

## 📦 Download

**🔗 [Download the latest .deb installer](https://github.com/corpest/spotify-overlay/releases/latest)**

_Use this if you don’t want to build from source._

---
## ⚠️ Important Note
also remember to install playerctl
```
## 🛠️ Building from source

1. Clone the repository:

    ```bash
    git clone https://github.com/corpest/spotify-overlay.git
    cd spotify-overlay
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. To run the app:

    ```bash
    npm start
    ```

---

## 📦 Packaging the App for Linux (Debian)

If you want to build the `.deb` installer package, you can do so using `electron-builder`:

1. Ensure that the necessary dependencies are installed:

    ```bash
    npm install
    ```

2. Build the `.deb` package:

    ```bash
    npm run dist -- --linux deb
    ```

This will generate the `.deb` installer file in the `dist/` directory, ready to be installed on your system.
