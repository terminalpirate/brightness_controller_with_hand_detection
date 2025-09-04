<h1 align="center">Brightness Controller with Hand Detection</h1>

This is a Python project that uses OpenCV and Mediapipe to see hand gesture and accordingly set the brightness of the system from a range of 0-100. 

![gif showing execution](./screenrecording.gif)

We have used a HandTracking module that tracks all points on the hand and detects hand landmarks, calculate the distance between thumb tip and index fingertip and maps the distance between thumb tip and index fingertip with brightness range.

# Building and running

## Install Required Libraries

*Note: Create a virtual environment before installing dependencies with venv (optional)*

**Mediapipe:** It is Google’s open-source framework, used for media processing. It is cross-platform or we can say it is platform friendly. It can run on Android, iOS, and the web that’s what Cross-platform means, to run everywhere.

```python3
pip install mediapipe
```
**OpenCV:** Itis a Python library that is designed to solve computer vision problems. OpenCV supports a wide variety of programming languages such as C++, Python, Java etc. Support for multiple platforms including Windows, Linux, and MacOS.

```python3
pip install opencv-python
```

**Screen-Brightness-Control:** It is a python tool for controlling the brightness of your monitor. Supports Windows and most flavors of Linux.

```python3
pip install screen-brightness-control
```

**Numpy:** It is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python.

```python3
pip install numpy
```

## Run the script

```python3
python script.py
```