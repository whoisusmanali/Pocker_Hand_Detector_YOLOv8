# Pocker_Hand_Detector
In this project, I used YOLOv8 for training the model and making the object detection. Further, the dataset was downloaded from Kaggle and train the model on YOLOv8 in Google Colab. After training the best.pt file was downloaded and used for detection, in which I prepared a whole different python Functions to detect the poker hand.


#Libraries/Dependencies Used:


1. CV
2. CvZone
3. Ultralytics
4. math
5. Numpy


# Step involved:

1. Download the dataset
2. Modify the data.yaml file from dataset accordint to needs.
3. Apply the YOLOV8 from ultralytics on the dataset (use Google colab if don't have GPU)
4. The file name with best.pt will be created on local machine
5. Download the best.pt file
6. Now make a new Poker-Hand-Detector.py file in any offline IDE.
7. Upload this best.pt file and do same coding as in Pocker-Hand-Detector.py
8. Make a new file PockerHandFunction.py for defining the roles of the Pocker Hand
9. Get this file in Main file that is Pocker-Hand-Detector.py
10. Apply the roles file and .pt file to get results.
11. Lastly, the results will shock you.


