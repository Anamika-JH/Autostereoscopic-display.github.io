# Hand Gesture Recognition for Autostereoscopic Display
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python) ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-red?style=flat-square&logo=opencv) ![Mediapipe](https://img.shields.io/badge/Mediapipe-Hand%20Tracking-orange?style=flat-square) ![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-Desktop%20Automation-brightgreen?style=flat-square) ![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey?style=flat-square)
This project enables gesture-based interaction using a webcam by recognizing hand gestures with the Mediapipe library and controlling the system via the PyAutoGUI library.

## Project Structure
The code for gesture interaction is located in the `Hand-Gesture-Recognition` folder. The project is divided into two main files:

- **`app.py`**: Contains the main program logic for capturing video and processing hand gestures.
- **`controller.py`**: Handles mouse cursor movement and click events based on detected gestures.

Additionally, a `requirements.txt` file is provided to install the necessary dependencies.

## Requirements
To run the program, the following libraries are required:
- OpenCV
- Mediapipe
- PyAutoGUI

### Installation
You can install the required libraries using pip:
```sh
pip install opencv-python mediapipe pyautogui
```
Or use the `requirements.txt` file to install the exact versions:
```sh
pip install -r requirements.txt
```

## How to Run
1. Ensure that all required libraries are installed.
2. Run the `app.py` file in a Python environment with a webcam:
   ```sh
   python app.py
   ```
3. The program will start capturing video from the webcam, and you can control the system using hand gestures.

## Gesture Reference
Images representing each hand gesture and their corresponding actions can be found in:
- `Hand-Gesture-Recognition/gestures/`

## System Schematic
The schematic of the setup is available in:
- `static/images/SYSTEM.png`

For more details, visit the project webpage: [Autostereoscopic Display](https://anamika-jh.github.io/Autostereoscopic-display.github.io/)


## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
