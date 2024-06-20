# Automatic Tracking and Charging Desktop

We create a automatic tracking and charging desktop. The approach was to use the STM32 U575ZI development board as the main control board, connected to an HC05 Bluetooth module and NEMA17 stepper motors to control the position of the wireless charging pad. A camera was used to monitor the phone's position, and a computer processed the camera footage using the YOLO v8 model to identify the phone's location. The location information was then transmitted to the STM32 development board via Bluetooth, which drove the motors to move the wireless charging pad under the phone to achieve active tracking and charging functionality.
This is a project fro MakeNTU 2024. We need to integrate hardware and software to develop an innovative product within a 24-hour hackathon.
The whole idea comes from this [video](https://www.youtube.com/watch?v=JrasYJDyg4Q)

To see how it work please watch the [video](https://drive.google.com/file/d/1D8ejN8aws75AzB3uTx0aBy2nEfk7af9W/view?usp=sharing) 
Our presentation slides [link](https://docs.google.com/presentation/d/15X92Lmv90sgRnkveBSQfuRx1iELKd2kf/edit?usp=sharing&ouid=102782269072995870803&rtpof=true&sd=true)

## Project Overview

- Hardware Implement
- Software Implement
- Others

### Hardware Implement

### Software Implement
We use YOLO v8 provided by ultralytics to detect the cellphone on the desktop and get the position of the cellphone. Since the camera resolution is quite bad. We use hundred of photos take by the camera and label the photos by Roboflow to fine tune the YOLO model.

### Others

