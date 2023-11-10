# Facial-Expression-Recognition

A CNN-based pytorch implementation on facial expression recognition (FER2013), achieving 94.62% Training Acc. and 63.91% Val Acc. This dataset was created as a competition to classify facial expressions using a Google search for facial expressions or synonyms of facial expressions. Note that the image sizes are 48x48, and contain posed and unposed images with very contrasting backgrounds. This code is using FER2013 dataset with keras library and tensorflow backend.

Image Properties: 48 x 48 pixels (2304 bytes)
Labels: 0 = Angry, 1 = Disgust, 2 = Fear, 3 = Happy, 4 = Sad, 5 = Surprise, 6 = Neutral
The Training (training) set consists of 28,709 examples, the PublicTest (validation) set consists of 3,589 examples, and the PrivateTest (test) set consists of another 3,589 examples.

To run this code:
1. Download FER2013 Dataset from https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
2. Run 'python main.py' 

## Image samples in the FER2013 Dataset ##
![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Faces.png)

## Dependencies ##
- Python 3.6+
- pip3 install pandas
- pip3 install numpy
- pip3 install sklearn
- pip3 install tensorflow
- pip3 install keras

## Visualize for image counts before inputting the data into the CNN model ##
![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Train.png)
![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Val.png)
![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Test.png)

NOTE: If the [Facial-Expression-Data-Visualization.ipynb](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Facial-Expression-Data-Visualization.ipynb) file does not open due to its length, then [click here](https://nbviewer.jupyter.org/github.com/daconjam/Facial-Expression-Recognition/blob/master/Facial-Expression-Data-Visualization.ipynb)


## Results ##
Due to a complex model, the training accuracy and training loss were very good; however, the test accuracy and test loss were poor as a result of overfitting.

![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Acc.png)


![Image text](https://github.com/daconjam/Facial-Expression-Recognition/blob/master/Images/Loss.png)
