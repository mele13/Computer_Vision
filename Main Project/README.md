# Main Project

This repository showcases a project focused on creating a set of four independent mini-games that leverage computer vision technologies, specifically using MediaPipe. The primary goal is to provide interactive and enjoyable experiences, with a special emphasis on enhancing mobility and potentially benefiting individuals with physical disabilities.

**Please Note: This project is developed solely for a university project.**

## Table of Contents
- [Main Project](#main-project)
  - [Table of Contents](#table-of-contents)
  - [Packages Used](#packages-used)
  - [Required packages](#required-packages)
  - [Project: Technical Description](#project-technical-description)
    - [Snake](#snake)
    - [Rock, Paper, Scissors](#rock-paper-scissors)
    - [Music](#music)
    - [Paint](#paint)
    - [Graphical Interface, Start, and Exit](#graphical-interface-start-and-exit)
  - [Collaborators](#collaborators)
  - [Disclaimer](#disclaimer)

## Packages Used
To run the code in the Jupyter notebooks, make sure you have the following packages installed:
- OpenCV (`cv2`)
- mediapipe (`mediapipe`)
- NumPy (`numpy`)
- pygame (`pygame`)
- os (`os`)
- math (`math`)

## Required packages
In order to ensure the proper functioning of the code, you need to install the following packages:

- OpenCV: a computer vision library for image and video processing.
   ```shell
   pip install opencv-python
   ```
- mediapipe: a library for building perception pipelines.
  ```shell
   pip install mediapipe
   ```
- NumPy (numpy): a library for numerical operations in Python.
  ```shell
   pip install numpy
   ```
- pygame: a cross-platform set of Python modules designed for writing video games.
  ```shell
   pip install pygame
   ```
- os: a module for interacting with the operating system in Python.
  ```shell
   pip install os-shutil-etc
   ```
- math: a module providing mathematical operations in Python.
  ```shell
   pip install math
   ```


## Project: Technical Description
The project entails the development of four standalone mini-games, harnessing computer vision technologies for precise and dynamic interaction. Each mini-game integrates specific modules from the MediaPipe library, enabling the detection and tracking of elements such as hands and faces.

### Snake
This segment involves the implementation of the classic Snake game, leveraging the MediaPipe Hands module for hand detection and tracking. The game encompasses the identification and tracking of pivotal hand points, including finger points and joints. Additionally, a configuration is integrated to allow the snake to seamlessly follow the movement of the index finger, offering an intuitive control mechanism.

### Rock, Paper, Scissors
The Rock, Paper, Scissors mini-game utilizes the MediaPipe Hands module for gesture detection, evaluating finger position and configuration. The game includes an analysis of predefined gestures to determine player movement, coupled with the program's ability to randomly generate gestures, serving as the user's virtual opponent.

### Music
In the Music mini-game, the MediaPipe Pose module is deployed for pose detection, assessing hand and foot position and configuration. The game incorporates the mapping of circle positions to trigger sound events on the base music when hands or feet are detected on these figures.

### Paint
The Paint mini-game implements the FaceMesh module for detecting and tracking key points on the face, specifically focusing on the nose. This involves the creation of a detailed three-dimensional facial mesh to represent facial topology. Furthermore, the position of a facial landmark (nose) is intricately linked to the action of painting a line using OpenCV.

### Graphical Interface, Start, and Exit
Beyond the mini-games, computer vision is integrated into managing and controlling the graphical interface, encompassing the initiation and termination of each mini-game. The MediaPipe Hands module is employed for gesture detection to evaluate finger position and configuration. The analysis of predefined gestures not only determines the selected game but also orchestrates the start and end actions.

https://github.com/mele13/Computer_Vision/assets/87198060/4c263d9a-d25f-4042-baae-f6f010f6aeaf

Documentation used:
- https://mediapipe-studio.webapps.google.com/home
- https://developers.google.com/mediapipe/solutions/guide
- https://opencv.org/

## Collaborators
- [Selene](https://github.com/SeleneGonzalezCurbelo)
- [Mele13](https://github.com/mele13)

Please note that the names listed below might be nicknames.

## Disclaimer
The files presented here are a modification of the original files created by [otsedom](https://github.com/otsedom/otsedom.github.io/tree/main/VC/Trabajo).

These tasks are developed exclusively for educational purposes as part of a university course. 

--------------------------------------------------

Feel free to explore, learn, and have fun with these tasks! If you have any questions or suggestions, please open an issue on the repository.
