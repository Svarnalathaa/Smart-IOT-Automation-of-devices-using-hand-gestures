# Smart-IOT-Automation-of-devices-using-hand-gestures

*This project enables the automation of devices using hand gestures. The system uses a laptop camera to capture hand gestures, and the gestures are processed using MediaPipe and OpenCV. An Arduino is used to control the devices based on the detected gestures.*

Installation :
        To get started with the project, you need to install the required Python modules.
        You can do this using pip:

bash

          pip install opencv-python
          
          pip install mediapipe

Hardware Requirements:
        Arduino board (e.g., Arduino Uno)
        Laptop with a built-in camera or an external webcam
        Electronic devices to be controlled (e.g., lights, fans)

Project Structure:
        The project consists of the following files:
              main.py: Contains the main application code for capturing and processing hand gestures.
              controller.py: Contains the code for interfacing with the Arduino to control the devices.


To run the application, use the following command:

bash

    python main.py


Example Hand Gestures:                                                                                                                                                                                         
        Open Hand: Turn on the light.       
        Closed Fist: Turn off the light.        
        Thumbs Up: Increase fan speed.      
        Thumbs Down: Decrease fan speed.
