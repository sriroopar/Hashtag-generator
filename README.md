# Hashtag-generator


## Introduction

This project aims to generate hashtags for random images. *Deep Learning* is used to generate a caption for the given image and a simple *Natural Language Processing* implementation allows creation of hashtags from the caption by obtaining synonyms for the key words in the caption.

## Dependencies

*  [Python 3](https://www.python.org/)
*  [Keras](https://keras.io/)
*  [OpenCV](https://opencv.org/)
*  [Natural Language Toolkit](https://www.nltk.org/)
*  [Flask](https://flask.palletsprojects.com/en/2.0.x/)
*  [TensorFlow](https://www.tensorflow.org/install/pip)

    
## How to run the code
Clone the Repository to Google Colab and execute the program.

* Since GPU capacities can affect the working of Tensorflow by decreasing the speed , its essential that we utilise Google colab because it allows GPU utilisation .

* Another advantage is that, Tensor flow and other supporting libraries are pre installed in Colab which paves way for easy access

## Algorithm

* First load the data set and install Flask web framework.

* Import modules that are necessary for the application.

* Create a deep learning model and train it using the data set so that the captions are generated.

* From the generated captions remove ambigious contents and obtain synonyms for the remaining words.

* Display the words and their coressponding synonyms in a hashtag format for the specified input image. 

## Example Output

![Sample Image](https://github.com/sriroopar/Hashtag-generator/blob/main/static/photo-1544568100-847a948585b9.jfif)
![Output](https://github.com/sriroopar/Hashtag-generator/blob/main/static/SharedScreenshot-min.jpg)




