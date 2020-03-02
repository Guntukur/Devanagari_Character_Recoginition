# Devanagari_Character_Recoginition
Deep Convolutional Neural Network for Devanagari character recognition 

The project makes use of Deep CNN's For devanagari character recoginition 
which had shown superior results than the 
traditional shallow networks which are used in many recognition tasks.It includes an addition of Dropout Layer and dataset increment
approach to improve test accuracy.
An accuracy of 98.07 % has been achieved.


Dataset for the training of the model is taken from [Kaggle](https://www.kaggle.com/rishianand/devanagari-character-set).It comprises of 92000 images [32x32 px]. There are 1024 input features of pixel values in grayscale (0 to 255). The column "character" represents the Devanagari Character Name corresponding to each image.

### Prerequisites
 Keras, TensorFlow, Scikit-learn, Seaborn, Matplotlib
 
 1.Install the project dependecies:
- Numpy : ``` $ pip install numpy```
- Scikit-learn : ```$ pip install -U scikit-learn``` 
- Matplot-lib : ```$ pip install matplotlib```
- Keras : ```$ pip install keras```
- seaborn : ```$ pip install seaborn```

2.Refer Devanagari_Character_Recoginition.ipnyb about Detailes of training and testing the model 
  


## Author

**[GUNTUKU SAI RISHITHA](https://www.linkedin.com/in/madhukar-kolli-2a512916b/)**

## Acknowledgments
### References
- [Devanagari Character Recognition](http://ashokpant.github.io/publications/ashok_2015_deep.pdf)
