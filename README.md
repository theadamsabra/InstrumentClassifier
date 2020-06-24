# Audio Classifier

![](images/mfcc.png)

### Overview:
A supervised classifier used to determine one of ten instruments given to it. The [full procedure](https://github.com/theadamsabra/Audio-Classifier/blob/master/Full%20Procedure.ipynb) can be read if interested. In the notebook there is preliminary exploratory data analysis, functions and methods developed to randomly sample data, as well as pipelines to preprocess and compare classification models. The classification methods compared in this data were Support Vector Classifier (SVC) and Gaussian Naive Bayes Classifier as they generalize well for high-featured data. The SVC significantly outperformed the Gaussian Naive Bayes and had a test accuracy of **98%**.

The data is a slice of the instruments that came from [Freesound General-Purpose Audio Tagging Challenge](https://www.kaggle.com/c/freesound-audio-tagging). Special thanks to [Seth Adams](https://github.com/seth814) for the Youtube Tutorial on how to interpret and clean the data as well as the sliced dataset being used in this repository.
