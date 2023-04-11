# Face-ID
deep learning face detection and identification using pyhton and opencv


Facial recognition technology is becoming more and more ubiquitous in our society, with applications ranging from unlocking smartphones to enhancing security measures in public spaces. One area where it can be particularly useful is in building security, where facial recognition can be used to identify people and grant them access to secure areas. In this project, we developed a facial recognition system using OpenCV and Python.

The system involves two main components: training the model and recognizing faces. To train the model, we first collected a dataset of images of people's faces, which we stored in a directory. We then used OpenCV's cascade classifier to detect faces in the images and extract them. We also assigned unique labels to each person in the dataset. Finally, we used the LBPH algorithm to train the model on the extracted faces and their corresponding labels.

Once the model is trained, we can use it to recognize faces in new images or video frames. We first detect faces in the image using the same cascade classifier and extract them. We then pass the extracted face through the trained model to predict the person's identity. If the predicted identity matches one of the labels in our dataset, we display the person's name. If the predicted identity does not match any of the labels, we display "Unknown".

We also added some additional features to our system, such as the ability to save and load trained models and the ability to adjust the confidence threshold for recognizing faces. By adjusting the confidence threshold, we can control the tradeoff between precision and recall in our recognition system.

In conclusion, we have demonstrated how to build a facial recognition system using OpenCV and Python. While this project is a simple implementation, it can serve as a starting point for more complex systems in real-world applications. As with any technology that involves personal data, it is important to consider ethical and privacy implications when deploying facial recognition systems.


## Installation

Install all the modules needed 

```bash
  pip install -r requirements.txt
```
    
