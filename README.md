# Face-detection-using-vgg16
Project Overview: Face Detection using VGG16 and TensorFlow

### Files:  

1) face_detection.ipynb: Contains the model training with 99% validation accuracy.
2) live_face_detection.py: Utilizes OpenCV for real-time face detection.
3) Demo Images: For testing purposes.
4) screen_shot.png (1 & 2):  Captures of live face detection.
5) hasrcasecade_face_frontage_default.xml:  Used for detecting face shapes in live footage.

### Dependencies:
1) Tensorflow(1.13.1)
2) Keras(2.3.1)
3) OpenCV2(4.1.1)
4) Python(3.7.7) 
5) Anaconda(4.7.11) 

Setup Instructions:
1) Download the entire repository.
2) Use your dataset.
3) Open and run all cells in face_detection.ipynb using Jupyter Notebook.

###Notebook Workflow:
- Import necessary libraries.
- Define variables (e.g., image_size, train/test paths).
- Download and integrate VGG16.
- Construct and train the model, validate, and plot accuracies.
- Test the model using a sample image.
- Save the model as 'Final_Model_Face.h5'.

###Live Detection (live_face_detection.py):

- Import libraries and load 'Final_Model_Face.h5'.
- Ensure webcam functionality.
- Use 'haarcascade_frontalface_default.xml' for live facial detection.
- Convert detected faces to array for model prediction.
- Display predictions (Ash, Malav, Nani) on live camera feed.
- For any issues, check paths and installed modules.

Thank you.  
Ashish  
linkedin : https://www.linkedin.com/in/ashishbarvaliya/  
