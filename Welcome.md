# Intellio Quarky Project Hub
Welcome to my collection of custom programs for the **Intellio Quarky** robot. This repository serves as documentation for my personal builds and a resource for the maker community.

*Note: I am an independent maker and not affiliated with STEMpedia.*

---

### Prerequisites

To run these programs, you must use the specific Alpha version of PictoBlox designed for the Intellio hardware:

1. **Download PictoBlox 9.1.0 for Windows (QUARKY INTELLIO – ALPHA Version)**
2. Install the application and ensure your Quarky is connected via USB or Bluetooth.
3. Switch to **Stage Mode** (top left toggle) to use the keyboard controls featured in this project.

## PC Keyboard Controlled Rover
This is my first project using the Quarky Rover build with the Mini Expansion Board. It features full manual control and a calibration sequence for the steering servo.

### Features
* **Driving:** Use **Up/Down** arrows for forward and reverse.
* **Steering:** Use **Left/Right** arrows to control the front wheels (Servo S1).
* **Speed Toggle:** Press the **Spacebar** to cycle through speeds (25%, 50%, 75%, 100%).
* **Visual Feedback:** LEDs change color based on movement (White for forward, Blue for reverse, Green/Red for turns).

### Logic Overview
Upon starting (Green Flag), the rover performs a center-left-right sweep to ensure the steering is aligned before operation.

### Download the Code

You can find the project file here:

### Getting Started
1. Download the `rover-control-v1.sb3` file from this respository. 
2. Open [PictoBlox].
3. Select **File > Open from your computer** and select the file.
4. Ensure you are in **Stage Mode** to use keyboard inputs.
