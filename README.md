# Human-Emotion-Detection
Recognised different facial expression e.g. Happy,Sad, Anger and Fear etc. using Convolutional Neural Network Model. Used Kaggle website dataset for the testing and training . 

To reduce the over fitting of model, used different techniques like Dropout and Batch normalization in addition to L2 regularization. 
Cross Validation technique was used to evaluate the performance of model.

## Dependencies
- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [TFLearn](https://github.com/tflearn/tflearn#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

## Dataset

We use the [FER-2013 Faces Database](http://www.socsci.ru.nl:8180/RaFD2/RaFD?p=main), a set of 28,709 pictures of people displaying 7 emotional expressions (angry, disgusted, fearful, happy, sad, surprised and neutral).

You have to request for access to the dataset or you can get it on [Kraggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).

## Usage

```bash
$ python emotion_recognition.py poc
```
