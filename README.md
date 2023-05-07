<H1 align="center">
YOLOv8 Object Tracking (ID + Trails) Blurring and Counting </H1>


## Steps to run Code

- Clone the repository
```
git clone https://github.com/noorkhokhar99/YOLOv8-Object-Tracking-ID-Trails-Blurring-and-Counting.git
```
- Goto the cloned folder.
```
cd YOLOv8-Object-Tracking-ID-Trails-Blurring-and-Counting
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/file/d/1q9CmLEXF4JDrAMwGpfJDMXAAC6LOJ0ne/view?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the detect folder

- put a Sample Video from the YOLOv8-Object-Tracking-ID-Trails-Blurring-and-Counting to detection  folder


- Run the code with mentioned command below.

- For yolov8 object detection, Tracking,  blurring and object counting
```
python predict.py model=yolov8l.pt source="test1.mp4" show=True
```

### RESULTS



### Watch the Complete Step by Step Explanation

[![Watch the video](https://github.com/noorkhokhar99/YOLOv8-Object-Tracking-ID-Trails-Blurring-and-Counting/blob/main/figure2.png)](https://www.youtube.com/watch?v=st9o5XqqNno)

