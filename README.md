# ROS_aruco_detection
Basic ROS node for aruco detection.

**Run the launch file and the python executable file separately**

# Note
Follow this link for setting up OpenCv depending on your ROS-distribution.
https://wiki.ros.org/vision_opencv

Sample code used from:
https://wiki.ros.org/cv_bridge/Tutorials/ConvertingBetweenROSImagesAndOpenCVImagesPython

I have used my computer's camera as the image source using the **usb_cam** ROS package. We can also use usb cameras.
**(For Raspberry pi: raspberry pi camera)**
Use the **rostopic** command for finding out the topic. I have subscribed to the "/usb_camera/image_raw" topic.
You can even use the "/usb_camera/image_raw/compressed" with the **Image_transport** ROS package.

I have used the aruco library in python for detecting Aruco Markers using OpenCV.
**Specify the aruco dictionary in code.**

