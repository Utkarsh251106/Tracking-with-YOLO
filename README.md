## Description
Tracking with YOLO is an object detection and tracking project designed to track and count the number of children and adults in a video. The dataset was annotated using Roboflow. For the actual execution of the program, the OpenCV library is used to handle camera and image-related tasks, NumPy is used for various mathematical calculations, and Ultralytics' YOLOv8 is used for object detection. Finally, the Deep SORT algorithm is used for tracking and occlusion prevention purposes. 

# How to run it?
### Step 1: Clone the Repository:
```bash
git clone https://github.com/Utkarsh251106/Tracking-with-YOLO
```
### Step 2: Create a conda environment:
```bash
conda create -n venv python=3.12.7 -y
conda activate venv
```

### Step 3: Install the requirements:
```bash
pip install -r requirements.txt
```
### Step 4: To run the code:
```bash
# Finally run the following command
python Code.ipynb
```
