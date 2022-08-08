## **YOLO Object Detection System**

💦 **Intoduction**

Here, the datasets of mask is taken and system is developed, which is capable of detecting mask in image and webcam using Yolo. 

💦 **Dataset Link:**

The dataset can either be created by web scraping or from kaggle
[Dataset](https://www.kaggle.com/datasets/aditya276/face-mask-dataset-yolo-format).

For the created dataset, labelImg software is used to create a .txt file having coordinates of the mask. This is done for the all images.


💦 **Steps to run the code:**
1. Create a virtual env.

2. Install all requirements using:
```
pip install -r requirements.txt 
```
3. Zip the dataset with corresponding .txt file in images.zip and upload to drive.
 
4. Run YoloV3_Training.ipynb in google colab for model training.

5. After completion of training ____.weights should be downloaded from drive.

6. To detect in image:
```
python test_on_photo.py
```  

5. To detect in live video:
```
python test_on_video.py
```

💦 **Outputs:**


    💧 Detections in Webcam

https://user-images.githubusercontent.com/43899969/183432272-650ccd71-3e98-4236-bc72-32ea33457759.mp4



    💧 Detections in Image

![image](https://raw.githubusercontent.com/rravii/YOLO_Object-Mask-_Detection_System/master/photo.JPG)

