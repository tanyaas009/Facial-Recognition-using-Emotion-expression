# Facial-Recognition-using-Emotion-expression
As we all know nowadays computer vision is getting advanced. major tech giants are building their models to become more like humans, to do so machines must be capable of detecting your emotions and treating you accordingly.  Here I have built a model using Tensorflow, which can tell you emotion using your picture or live webcam feed.
To train the model, we used Fer2013 datset that contains 30,000 images of facial expressions grouped in seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise and Neutral. It is available publicly on Kaggle. Here is the link: https://www.kaggle.com/datasets/ashishpatel26/facial-expression-recognitionferchallenge
Then we pre-processed the data. Here X_train, X_test contains pixels, and y_test, y_train contains emotions.
Then we reshaped the data and used Image data augmentation to improve the performance and ability of the model.
Then we designed the CNN model for emotion detection using functional API. We are creating blocks using Conv2D layer, Batch-Normalization, Max-Pooling2D, Dropout, Flatten, and then stacking them together and at the end-use Dense Layer for output.
