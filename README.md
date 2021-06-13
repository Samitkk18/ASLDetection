# American Sign Language Classification using OpenCV

## Steps to make this project working

### 1. Clone this repository 
    
    git clone https://github.com/Samitkk18/ASLDetection.git
    
### 2. Install the requirements

    pip install -r requirements.txt

### 3. Make your own Dataset

Go to <a href="https://github.com/Samitkk18/ASLDetection/blob/master/Tensorflow/scripts/GetDataScirpt.ipynb">here</a> and run this script.

### 4. After creating your dataset you need to label the images
Step 1: Clone this repository in Tensorflow/ folder.

    https://github.com/tzutalin/labelImg

Step 2: After cloning put resource.py and resource.qrc in libs folder 

Step 3: Run the file.

    python labelImg.py
    
### 5. After labelling the images split them into train and test folders <a href="https://github.com/Samitkk18/ASLDetection/blob/master/Tensorflow/workspace/images/">here</a>

### 6. Now follow the steps in <a href="https://github.com/Samitkk18/ASLDetection/blob/master/ASLDetection.ipynb">SignDetection.ipynb</a>
