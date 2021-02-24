# Instrument Classifier

![](images/mfcc.png)

### Overview:
A supervised classifier used to determine one of ten instruments given to it. The classification methods compared in this data were Support Vector Classifier (SVC) and Gaussian Naive Bayes Classifier as they generalize well for high-featured data. The SVC significantly outperformed the Gaussian Naive Bayes and had a test accuracy of **98%**. You can read the [full procedure](https://github.com/theadamsabra/Audio-Classifier/blob/master/Full%20Procedure.ipynb), if interested. In it, details the three main steps of the project:

- Exploratory Data Analysis and Data Cleaning
- Model Preparation of Data
- Model/Pipeline Building

The main objective of this project was for me to become more familiar with how audio data is structured and processed in models - so developing an instrument classifier with a relatively simple dataset was the best first step in this pursuit. The data is a batch of ```.wav``` files which have their resepective instrument labels in a seperate ```.csv``` file. They are a slice of the instruments that came from [Freesound General-Purpose Audio Tagging Challenge](https://www.kaggle.com/c/freesound-audio-tagging). Special thanks to [Seth Adams](https://github.com/seth814) for the Youtube Tutorial on how to interpret and clean the data, the sliced dataset being used in this repository, as well as [eda.py](https://github.com/theadamsabra/Audio-Classifier/blob/master/eda.py) to ease the visualization process in the EDA portion of the project.
