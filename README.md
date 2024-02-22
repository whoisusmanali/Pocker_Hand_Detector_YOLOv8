# Poker_Hand_Detector
Poker Hand Detector simplifies the understanding of poker hands for beginners worldwide. Leveraging computer vision, it accurately analyzes card arrangements. With a dataset sourced from roboflow.com featuring over 500 card images, the project ensures comprehensive coverage.

Powered by the YOLOv8 model, the detector achieves an impressive 98% accuracy in object detection. This state-of-the-art architecture enables precise identification of poker hands, enhancing the user experience.

Deployed on Flask, the Poker Hand Detector offers a user-friendly interface for seamless interaction. It enables users to effortlessly assess card combinations and determine winning probabilities, thereby facilitating informed decision-making during gameplay.

# Libraries/Dependencies Used:
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

# Pocker Hand Rules:

1. "KH", "AH", "QH", "JH", "10H"     (Royal Flush)
2. "QC", "JC", "10C", "9C", "8C"     (Straight Flush)
3. "5C", "5S", "5H", "5D", "QH"      (Four of a Kind)
4. "2H", "2D", "2S", "10H", "10C"    (Full House)
5. "2D", "KD", "7D", "6D", "5D"      (Flush)
6. "JC", "10H", "9C", "8C", "7D"     (Straight)
7. "10H", "10C", "10D", "2D", "5S"   (Three of a Kind)
8. "KD", "KH", "5C", "5S", "6D"      (Two Pair)
9. "2D", "2S", "9C", "KD", "10C"     (Pair)
10. "KD", "5H", "2D", "10C", "JH"    (High Card)



# Screenshots:
![image](https://github.com/whoisusmanali/Pocker_Hand_Detector_YOLOv8/assets/104086680/913c93c7-bc97-4408-a6e1-e2d59c8615e5)

![image](https://github.com/whoisusmanali/Pocker_Hand_Detector_YOLOv8/assets/104086680/351038ce-6499-4e8d-8b60-7c89a59ce0a5)

![image](https://github.com/whoisusmanali/Pocker_Hand_Detector_YOLOv8/assets/104086680/87572c14-2020-407f-9109-0ddf1e5f49aa)

![007134164_jpg rf aa5e36d250cc2cf6323201fb9b99068d](https://github.com/whoisusmanali/Pocker_Hand_Detector_YOLOv8/assets/104086680/846b8a8f-8a29-4e77-82af-8156a8dd0597)





