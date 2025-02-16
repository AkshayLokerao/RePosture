# Serial Monitor Viewer for RePosture

This project provides a web-based interface to view serial monitor output directly in your browser. It uses the Web Serial API to connect to an ESP32 device running the RePosture firmware, allowing real-time posture monitoring data.

## Features
- 📡 **Real-Time Serial Data:** View live posture readings in the browser.
- 🎨 **Dynamic UI:** Gradient background with a modern, sleek design.
- 🔌 **Easy Connection:** One-click connection to the ESP32.
- 🖥️ **Auto-Scroll:** Automatically scrolls to show the latest data.

## Prerequisites
Ensure you have:
- Google Chrome or any browser supporting the Web Serial API.
- ESP32 with the RePosture firmware installed.

## How to Use
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/reposture-serial-monitor.git
    cd reposture-serial-monitor
    ```

2. Open the `index.html` file in a compatible browser.

3. Click the **"Connect to your RePosture"** button.

4. Select the correct COM port for your ESP32 device.

5. Monitor the real-time posture data displayed in the black output window.

## Troubleshooting
- **No data displayed?** Ensure your ESP32 is sending serial data at `9600` baud rate.
- **Connection errors?** Replug the device and refresh the page.

## Sample Output
```
Posture: Good
Posture: Poor - Please correct your posture
Posture: Corrected
```

## License
This project is licensed under the MIT License. 

**Happy Monitoring! 🦾**

