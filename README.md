# skin-lesion-classifier


classify skin lesions using Deep learning (convolutional neural network)

## Getting Started

 [kaggle Dataset of skin lesions](http://www.dropwizard.io/1.0.2/docs/)  consists of 10015 images which describe 7 type of lesions.

Our goal is to build the best classifier and find the best technique to classify this lesions with high accurcy.

Or maybe getting ideas about building new hardware to get it more easier to be detected.

lets go 


### Prerequisites

you should have first 'any python IDE' Irecomend anacona or just work on colab if your gpu is not good.


You need keras machine learning library and other liberaries like numpy ,pandas and opencv which dealing with images and arrays and csv files

```
pip install Keras
pip install numpy
pip install pandas 
if you will work on your local pc (not recommended) 

```

### Installing

If you will work on your local pc you need a lot of libraries but the most important one is the "pip"

It's built in in python 3.6 and higher 

after setup python

open CMD 

A fast way to launch this window is to press the Win + R keys on your keyboard. Then, type cmd and press Enter or click/tap OK
```
in cmd write this orders

pip install numpy
pip install opencv
pip install pandas
pip install keras

```


## Running the tests for liberaries

check if you install it well

open python script 
then write
``` 
import cv2
import numpy 
import pandas
import keras
```


## Results 
unforchanitaly the 3 models give the same accurcy 

due to 

* unbalance data

which mean each class doesn't have the same amount of data so the model becomes [Biased]

solutions will be add to this problem

* the data itsalf 

not clear and the normal camera'RGB' _i think it isn't suitable for scan like this , we need multispectral imaging _





## Built With

* [Google colab](https://colab.research.google.com/) - free cloud GPU provided from google for research
* [kaggle dataset](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) - dataset center 






## Authors

* **Sayed mohamed**  - [sayed mohamed](https://github.com/sayedmohamedscu)




## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments


* [Transfer learning](https://nbviewer.jupyter.org/github/fchollet/deep-learning-with-python-notebooks/blob/master/5.3-using-a-pretrained-convnet.ipynb)
* [Medium](https://medium.com/)
