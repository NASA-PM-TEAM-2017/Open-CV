Team:

1. I hope that your break went well and I am looking forward to working with you in the up coming semester. I have included a list of items that I would like you to look over before we meet next week.  Lets meet Monday around lunch time as I am meeting with Jack's robotics group to discuss the implementation of OpenCV for python. Time and location to follow.

2. http://ameridroid.com/  There are a number of single board computers that are of interest.  The XU4 is our primary target.  also visit http://www.hardkernel.com/main/main.php.  

3. Please download the manual for the XU4 and also look at the camera in this link http://ameridroid.com/products/ocam-1mgn-u-usb3-dot-0-global-shutter-camera

4. Review the 3DR Pixhawk and materials:: https://pixhawk.org/

5. Review the code installation:: Dronekit:: http://dronekit.io/

6. Review install and know how to use:: Codeblocks and g++ compilers (CB::http://www.codeblocks.org/  and mingw:: https://sourceforge.net/projects/mingw/files/latest/download?source=files ):: There are a couple of installations that we will need to use the full power of the board io, camera, and arduino sub-controlers.  This will allow us to develop a better path with other enginnering paths and the camera only runs in C++ with the needed libraries (more to come on this).  

7. Computer vision library:: OpenCV there are two implementations that we will use.  The first is the Python based opencv library which as you know is simple to install and use.  Second is the C++ implementation of the opencv code with much greater functionality and control.  Sadly I've not yet been able to get this working in even the smallest way.  This is a hurdle that we must overcome as the Python based library does not have the necessary power as it is installed.  In particular, the global shutter camera-which is important because it read the data from the pixels in a way that will not distort the image- can only be run in C++/C environments.


Quick process overview::

pix hawk does the flying:: XU4 handles the camera and connects to pix hawk with Drone kit :: commands to the pix hawk are written in python:: OpenCV and camera processing are done on the XU4 with applications developed in code blocks with opencv with simple outputs to Python Drone kit controller.  
