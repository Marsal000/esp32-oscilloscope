# ESP32 Web Oscilloscope

A modern **Web Bluetooth Oscilloscope** built with **ESP32** and a browser-based interface inspired by professional digital oscilloscopes.

Connect directly to your ESP32 from Google Chrome without installing any desktop software.

The project combines an ESP32-based data acquisition system with a responsive HTML5 web application that provides real-time waveform visualization, trigger controls, live measurements, and an intuitive oscilloscope-style interface.

> **No drivers. No software installation. Just open the webpage and connect.**

---

## Features

* Real-time waveform rendering
* Web Bluetooth connectivity
* No desktop software required
* Scoppy-inspired oscilloscope interface
* Adjustable Time/Div
* Adjustable Volts/Div
* Horizontal Position control
* Vertical Position control
* Trigger Modes

  * Auto
  * Normal
  * Free Run
* Rising/Falling Edge Trigger
* Live Measurements

  * Frequency
  * Vmax
  * Vmin
  * Vpp
* Demo Mode for testing without hardware
* Fullscreen Mode
* Responsive UI for Desktop and Mobile
* Optimized rendering using `requestAnimationFrame`
* BLE packet reassembly for reliable waveform streaming

---

## Live Demo

The web application is hosted using GitHub Pages.

```
https://marsal000.github.io/esp32-oscilloscope/
```

---

## Browser Compatibility

| Browser                 | Support                       |
| ----------------------- | ----------------------------- |
| Google Chrome (Desktop) | Supported                       |
| Microsoft Edge          | Supported                       |
| Chrome on Android       | Supported                             |
| Firefox                 | Web Bluetooth ot supported |
| Safari                  | Web Bluetooth not supported |

> **Note:** Web Bluetooth is currently supported only in Chromium-based browsers.

---

## Getting Started

1. Open the hosted web application or download `index.html`.
2. Open it in **Google Chrome** or **Microsoft Edge**.
3. Click **CONNECT DEVICE**.
4. Select your compatible ESP32 device.
5. Click **RUN** to begin streaming data.

> The firmware used by the hardware is currently **not part of this repository**.

---

## User Interface

### Horizontal

* Time/Div
* Horizontal Position

### Vertical

* Volts/Div
* Vertical Position

### Trigger

* Trigger Level
* Rising/Falling Edge
* Auto Trigger
* Normal Trigger
* Free Run

### Measurements

* Frequency
* Peak-to-Peak Voltage (Vpp)
* Maximum Voltage (Vmax)
* Minimum Voltage (Vmin)

---

## License

This repository currently contains only the web application interface.

The firmware is not included at this time.

---
