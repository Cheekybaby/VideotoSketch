## Live Image to Sketch Generator ##

This project is based on different live filters implemented on different platforms like Snapchat, etc.
This is a beginner project made to understand the different concepts in OpenCV and Image Processing Techniques like Image Segmentation, etc. by applying it to make a filter on live input source.

This project contains 4 main files namely engine.py, main.py, pencilSketch.py, and selfieSegmentation.py.
The engine.py is a custom object built to process webcam streams, video sources or images.
The selfieSegmentation.py is a custom object built for the segmentation of the foreground from the background.
The pencilSketch.py is the custom object that implements Gaussian Blur and Dodge to remove noise and sharpen the foreground from the background respectively. This contains the program that creates a filter on the incoming frames.
The main.py file is used to assemble every object in order to build a live image-capturing program that can convert the incoming frames to a specified filter (here, Sketch).

For more filters, add more files like pencilSketch.

P.S. Manually tune the blur sigma and sharpen value attributes in the main.py file depending on the lighting conditions in the test environment.
