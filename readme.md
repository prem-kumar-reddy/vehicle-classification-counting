Unzip the file

Main.py file has required code to run the demo. 

Main.py runs YOLO V3 Network with configuration stored in yolov3-320.cfg,
then, detects the vehicles, classify them based on confidence, 
uses tracker.py to track them, and then counts the detected vehicles under
respective category.

To run model on videos, edit the variable "video_file" with availble 
  video file names and uncomment realTime() function invocation in Main function, comment remaining code.

To run model on Images, edit the variable "directory" value with Image folder
  path comment realTime() function invocation in Main function and, uncomment
  reamining code which is to access Image Dataset and render model on it.
  China Highway Image Dataset is available at http://drive.google.com/open?id=1li858elZvUgss8rC_yDsb5bDfiRyhdrX (7.38GB)