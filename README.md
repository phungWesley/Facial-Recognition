# Facial-Recognition
Contributers: Taylor Nguyen (tnguyen7871@sdsu.edu) , Wesley Phung (wphung3516@sdsu.edu)

Prerequisities: 
- OpenCV 3.2 or newer
- Tensorflow 1.7.0 or newer (optional)
- Python 3.9 or newer
- Fer 

OpenCV, Tensorflow, and Fer libraries can be installed via 'pip install'
To ensure to check your python version, type 'python -V'; if it not 3.6 or newer, visit the Python downloads page to update to the latest version.

Packages: 
- cv2
- numpy
- logging
- os
- pkg_resources
- requests
- sys
- tqdm 

Troubleshooting installing packages : 
In the event that there are issues with installing these packages, one main issue may be due to the fact 
Python is not on its latest version. As stated in the prerequisite, Python 3.9 or newer is required as some packages were deprecated in older versions of Python
where these packages are unable to be installed. This should resolve the issues for most cases; however, in the event that installation issues still persist, the imported package(s) were not able to be located. To solve this, try to run the terminal command: PIP INSTALL [PACKAGE].

Usage:
1. First, ensure all the prerequisities, packages above are installed, and folders under Facial-Recognition are installed.
2. As this facial recognition takes in video samples, ensure the parameter in the video_filename = "[samplevideo].mp4" is updated to the desire input.
3. Run visualizer.py through any terminal.
4. The program will begin processing the file and once it is done, it will output a chart with 7 emotions emoted over time in a graph and a bar plot of all emotions below. Additonally, this will output an excel sheet of the value of each emotion from each frame of the video in a separate folder. A video will also be attached with its facial detection and emotion recognition algorithm being displayed throughout the video. 

Additional Resources:
- https://github.com/opencv/opencv/tree/master/data/haarcascades : includes many other models that recognize specific facial features, body parts, and more. In this project, we used the model: frontal_face_default
