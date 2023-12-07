# Fourth Assignment

This repository contains practical exercises and code related to computer vision. Each task is accompanied by a description, code implementation, and documentation.

**Please Note: This project is developed solely for a university project.**

## Table of Contents
- [Fourth Assignment](#fourth-assignment)
  - [Table of Contents](#table-of-contents)
  - [Packages Used](#packages-used)
  - [Required packages](#required-packages)
  - [Task: Real-time Facial Feature Overlay](#task-real-time-facial-feature-overlay)
    - [Accessories Augmentation Modes](#accessories-augmentation-modes)
  - [Collaborators](#collaborators)
  - [Disclaimer](#disclaimer)

## Packages Used
To run the code in the Jupyter notebooks, make sure you have the following packages installed:
- OpenCV (`cv2`)
- NumPy (`numpy`)
- Tkinter (`tkinter`)
- math (`math`)
- os (`os`)
- numpy (`numpy`)
- time (`time`)

## Required packages
In order to ensure the proper functioning of the code, you need to install the following packages:

- Retina-Face: a face detection package that provides accurate results.
   ```shell
   pip install retina-face
   ```
- IPykernel (Anaconda): only if you encounter the 'ipykernel package required' error:
    ```shell
    conda install -c anaconda ipykernel
    ```
- DeepFace: used for deep learning-based face recognition tasks.
    ```shell
    pip install deepface
    ```
- Imutils: provides utility functions for working with OpenCV.
    ```shell
    pip install --upgrade imutils
    ```
- CMake: required for building some packages, such as dlib.
    ```shell
    pip install cmake
    ```
- Dlib (Conda Forge): a dependency for some face-related tasks and requires CMake for installation.
    ```shell
    conda install -c conda-forge dlib
    ```
- Dlib (PyPI): a C++ library with Python bindings used for various computer vision tasks.
    ```shell
    pip install dlib
    ```
- MTCNN: a face detection package that can be used in conjunction with other methods.
    ```shell
    pip install MTCNN
    ```
- TensorFlow is a deep learning framework that may be required by some models and face recognition tasks.
    ```shell
    pip install tensorflow
    ```
Make sure to install these packages in your environment to ensure the correct operation of the provided code. The reasons for installing each package are also provided for clarity.

**Note**: If the .dat files do not work, you can download them from this link: http://dlib.net/files/

## Task: Real-time Facial Feature Overlay
This task involves creating a code prototype that utilizes facial data without thematic constraints. Advanced detectors provide insights into facial components, opening up opportunities for diverse applications, including creative filters.
The solution is a code that offers real-time facial feature overlays using live video input. This prototype seamlessly integrates OpenCV, Tkinter, and NumPy libraries to accomplish the task. Users can experiment with facial feature overlays in a creative and interactive manner, choosing from various modes for an engaging experience.
Documentation used:
- https://github.com/italojs/facial-landmarks-recognition/tree/master
- https://python.hotexamples.com/examples/retinaface/RetinaFace/build_model/python-retinaface-build_model-method-examples.html
![Sheldon's demonstration gif](./Images/sheldon_demonstration.gif)

### Accessories Augmentation Modes
Available modes for augmenting facial accessories in real-time:
1. **Hats**: This mode allows users to try on different hats, adjusting their position and size according to the detected face.
2. **Glasses**: Users can experiment with various glasses styles, ensuring a proper fit to the face.
3. **Lips**: Experiment with different lip colors and shapes, enhancing your facial appearance.
4. **Moustaches**: Instantly add moustaches in various styles and sizes to see how they complement your face.
5. **Beards**: Explore different beard styles, adjusting their position and size as needed.

## Collaborators
- [Selene](https://github.com/SeleneGonzalezCurbelo)
- [Mele13](https://github.com/mele13)

Please note that the names listed below might be nicknames.

## Disclaimer
The files presented here are a modification of the original files created by [otsedom](https://github.com/otsedom/otsedom.github.io/tree/main/VC/P4).

These tasks are developed exclusively for educational purposes as part of a university course. 

--------------------------------------------------

Feel free to explore, learn, and have fun with these tasks! If you have any questions or suggestions, please open an issue on the repository.
