# Xojo and OpenCV
### http://opencv.org/
### https://www.xojo.com

## *This binding requires OpenCV 3.0!*
## *Windows users are required to install ffmpeg for movies decoding*##

### Updated Version
Based on  Antonio Rinaldi's suggestion: access to OpenCV is  declared once in /xTools as a constant.Easier to adapt or modifiy to new version of OpenCV.

Then path to libs is relative to the included Framework (e.g @executable_path/../Frameworks/OSX/libopencv_world.3.0.0.dylib)

So build app is fully usable in a system where OpenCV is not installed



### February 2016
New samples addedPre-compiled libraries for OSX, Linux and Windows added

Enjoy :)

## Warning
You must use 32-bit version of OpenCV and ffmpeg dynamically linked libraries. 
Work under progress at Xojo for 64-bit!

The code is under development. This software is provided 'as-is', without any express or implied warranty. 

## More OpenCV functions and samples to come. 
Optimization for xojo projects

**2015-09-13: A new module in OpenCV folder (xTools) for converting OpenCV images to Xojo Picture**

**2015-09-14: New video directory : how to read movies with openCV**

**2015-09-14: Updated samples for OSX and Windows 10**

**2015-09-16: Updated samples with trackbar and mouse events**

**2015-09-17: objdetect and calib3d modules implemented**

**2015-09-23: imgproc and core modules are completed. New samples included**





## Getting Started
Very easy. Just unzip the downloaded file and open OpenCVX code with Xojo IDE. Then drag the **OpenCVX folder** to any application requiring OpenCV image processing. 

**OPenCVX folder** contains different **modules** that give access to various OpenCV functions that are declared as External Methods.

Inside each module there is a **constant** (e.g. core, immproc, highgui..) which is linked to  OpenCV libraries. 

**PLease update values according to your OS.**


## samples dir
Several programs which demonstrate how to use OpenCV with Xojo are included in the **samples** directory .
These programs allow to play with camera and images.
Some morphological operators sample are introduced


## enjoy


