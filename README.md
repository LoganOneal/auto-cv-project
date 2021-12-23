
- [Objectives](#objectives)
- [Resources](#resources)
  - [Option 1](#option-1)
  - [Option 2](#option-2)
- [Data](#data)


## Objectives
1. Identify vehicles in a video
2. Create a way to count cars passing by over time
3. Log timestamps of each car
4. Log speed of each car
## Resources 

### Option 1
* [T-Analyst](https://bitbucket.org/TrafficAndRoads/tanalyst/wiki/Manual) can be used to analyze traffic videos in MP4, AVI, and MKV format. This is a great place to start. Simply follow the download instructions and run the software. 
* When using T-Analyst make sure you read the manual in the folder that comes with the software. 

    ![T-Analyst](https://i.imgur.com/BxZvStE.png "T-Analyst")

### Option 2
* This option will require some coding. [OpenCV](https://opencv.org/) is a software library for image processing. I would reccomend using python and installing through pip `pip install opencv-contrib-python`. There are a couple of approaches you could take to accomplish the object detection. You could create a filter based on pixels changing and blob size [see OpenCV docs](https://docs.opencv.org/3.4/d0/d7a/classcv_1_1SimpleBlobDetector.html) or you could even use ML through something such as the [YOLO](https://www.codespeedy.com/yolo-object-detection-from-image-with-opencv-and-python/#:~:text=YOLO%20is%20an%20object%20detection%20algorithm%20or%20model,entire%20image%20in%20one%20go%20and%20detects%20objects.) model which is trained to identify cars. 

    ![OpenCV](https://i.ytimg.com/vi/Q3RXwBAP-dk/hqdefault.jpg "YOLO OPENCV")


## Data

- Download this [video](https://drive.google.com/file/d/1N5wV9OVsMDInEIPbmgtwPi23dcVUtUAA/view?usp=sharing) to start. If you need more test footage just google traffic video and there are lots of options. 
  


