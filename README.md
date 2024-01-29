# Computer_Vision_Project

# **1. Track and Count Vehicles using yolov8**

**Overview**

This project utilizes the YOLOv8 object detection model along with ByteTrack for advanced vehicle tracking and counting in videos. The aim is to automatically identify, follow, and count different types of vehicles, such as cars, buses, and bikes, which can be useful in traffic analysis and parking management.

**Requirements**

a. Python 3.x

b. Ultralytics YOLOv8

c. ByteTrack

d. Additional Python libraries as specified in the notebook (e.g., OpenCV, NumPy)

e. Access to a GPU for efficient processing (NVIDIA GPU recommended)

**Setup**

a. Clone the repository or download the project files.

b. Install required Python libraries: pip install -r requirements.txt (Create this file based on the notebook's imports).

c. Download the YOLOv8 pre-trained weights from Ultralytics and set up ByteTrack.

**Usage**

a. Ensure that a GPU is available for processing (check with nvidia-smi).

b. Place your video files in the specified directory.

c. Run the Jupyter Notebook: Track_and_Count_Vehicles_using_yolov8.ipynb.

d. The notebook will process the video frames to detect, track, and count vehicles.

**How It Works**

a. The notebook uses YOLOv8 for object detection to identify vehicles in the video frames.

b. ByteTrack is used to track the detected vehicles across the frames.

c. The system counts each type of vehicle and can be used for various applications like traffic pattern analysis.

**Acknowledgments**

a. Ultralytics for the YOLOv8 model.

b. ByteTrack developers.

# **2. Speed Estimation using Ultralytics YOLOv8**

**Overview**

This project is designed to estimate the speed of vehicles using the Ultralytics YOLOv8 object detection model. The project processes video frames to detect vehicles and estimate their speeds.

**Requirements**

a. Python 3.x

b. Ultralytics YOLOv8

c. Additional Python libraries as specified in the notebook (e.g., OpenCV, NumPy)

**Setup**

a. Clone the repository or download the project files.

b. Install required Python libraries: pip install -r requirements.txt (You may need to create this file based on the notebook's imports).

c. Download the YOLOv8 pre-trained weights from the Ultralytics website or train your own model.

**Usage**

a. Place your video files in the designated directory.

b. Run the Jupyter Notebook: Speed_Estimation_using_Ultralytics_YOLOv8.ipynb.

c. The notebook will process the video frames, detect vehicles, and estimate their speeds.

**How It Works**

a. The notebook uses the YOLOv8 model for object detection.

b. It processes each frame of the input video to detect vehicles.

c. The speed of each vehicle is estimated based on the detected bounding boxes and frame rate.

**Acknowledgments**

a. Ultralytics for the YOLOv8 model.

b. Any other sources or contributors you wish to acknowledge.

