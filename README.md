# 🧛 Dracula OLED Lyric Visualizer

An ESP32-powered OLED lyric visualizer inspired by the song **"Dracula"**. This project displays synchronized lyrics alongside dynamic animated backgrounds, creating a unique cyberpunk-style visual experience on a 128×64 OLED display.

---

## ✨ Features

* 🎵 Word-by-word lyric synchronization
* 🌧️ Matrix Rain animation
* 📡 Radar Sweep effect
* 📈 Oscilloscope waveform visualization
* 📺 TV Static glitch effect
* 🔷 Pulsing Hex Grid animation
* 🚀 Warp-Speed Starfield effect
* ⚡ Dynamic text animations (Pop, Shake, Glitch, Invert, Zoom)
* 🔄 Automatic looping playback
* 📟 Supports both SSD1306 and SH1106 OLED displays

---

## 🛠 Hardware Required

| Component                              | Quantity  |
| -------------------------------------- | --------- |
| ESP32 Development Board                | 1         |
| 128×64 OLED Display (SSD1306 / SH1106) | 1         |
| Jumper Wires                           | As Needed |

---

## 📚 Libraries Required

```cpp
Adafruit GFX Library
Adafruit SSD1306 Library
Adafruit SH110X Library
Wire Library
```

---

## 🔌 Wiring

### OLED → ESP32

| OLED Pin | ESP32 Pin |
| -------- | --------- |
| VCC      | 3.3V      |
| GND      | GND       |
| SDA      | GPIO 21   |
| SCL      | GPIO 22   |

---

## 🎬 Effects Showcase

The visualizer automatically switches between different animated backgrounds depending on the currently displayed lyric.

### Available Effects

* Matrix Rain
* Radar Scanner
* Oscilloscope
* TV Static
* Hex Grid Pulse
* Warp Drive Starfield

Each lyric can trigger a different text animation to enhance the visual impact.

---

## 🚀 Getting Started

1. Install the required libraries.
2. Connect the OLED display to the ESP32.
3. Upload the sketch.
4. Enjoy the Dracula lyric visualizer.

---

## ⭐ Support

If you found this project interesting, consider giving the repository a star.

---


Made with ❤️ using ESP32 and OLED Displays.
