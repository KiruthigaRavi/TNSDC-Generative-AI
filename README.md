
## "MaskNet: Real-Time Mask Detection using Convolutional Neural Networks with TensorFlow"
This project discusses the importance of facial mask detection in public areas and outlines the methodology involving neural networks like CNN architecture, alongside real-world testing results.
It also explores future directions focusing on improvements, applications, and the project's role in reducing the spread of infectious diseases.
## DATASET 
LINK: [https://www.kaggle.com/datasets/andrewmvd/face-mask-detection](url)
## WORKING
For preprocessing the data, we employed OpenCV libraries like cv2 and os.
We initialized two empty lists, "data" and "target." The "data" list stored grayscale images, while the corresponding labels ("with mask" and "without mask") were appended to the "target" list. 
Using numpy, we loaded these arrays into a CNN model constructed with Keras models and layers, incorporating operations like flattening and pooling. 
Subsequently, the data underwent splitting into training and testing sets, with callback functions utilized to save the model at each epoch's end.
Visualization techniques, such as matplotlib, aided in providing a comprehensive overview of the data. 
Lastly, in the detection model, we utilized CascadeClassifier and videocapture to detect faces with masks highlighted in green boxes and without masks in red.

<a href="url"><img src="[http://url.to/image.png"](https://github.com/KiruthigaRavi/TNSDC-Generative-AI/assets/104771518/584c93a0-609e-4459-8f7c-e4e50c0541ad) align="left" height="48" width="48" ></a>
