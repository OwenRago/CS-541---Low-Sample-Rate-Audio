## CS 541 Deep Learning Final Project: Low-Sample Rate Audio Classification Study
###### By: Jack Adiletta, Blake Bruell, Jeffrey Chan, and Owen Rago

#### Data Visualizing

This contains all the notebooks used to create our charts. It also has all of the chart files and the data which was used.

#### Data Processing

This contains the notebook to pre process all the audio data.
Here is a [link](https://urbansounddataset.weebly.com/urbansound8k.html) to the website to the request the data set.
It can also be found on [Kaggle](https://www.kaggle.com/code/prabhavsingh/urbansound8k-classification)

Change fold_paths to to the path of your folder. Make sure to keep this to iterate through the files properly
```python
/fold{i+1}/ for i in range(10)
```

#### Models

This contains both model training and testing notebooks. In order to run change BASE_DIR to path to your sound data