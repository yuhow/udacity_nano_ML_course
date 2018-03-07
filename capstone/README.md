# Machine Learning Engineer Nanodegree
# Capstone
## Project: TalkingData AdTracking Fraud Detection Challenge (Kaggle Competition)

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [keras]
- [Tensorflow]

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

TBD.

### Run

In a terminal or command window, navigate to the top-level project directory `capstone/` (that contains this README) and run one of the following commands:

```bash
ipython notebook capstone.ipynb
```  
or
```bash
jupyter notebook capstone.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

All the data can be download from: https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data

**Features**
Each row of the training data contains a click record, with the following features.

- **ip**: ip address of click.
- **app**: app id for marketing.
- **device**: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
- **os**: os version id of user mobile phone
- **channel**: channel id of mobile ad publisher
- **click_time**: timestamp of click (UTC)
- **attributed_time**: if user download the app for after clicking an ad, this is the time of the app download 
- **is_attributed**: the target that is to be predicted, indicating the app was downloaded
Note that ip, app, device, os, and channel are encoded.

The test data for Kaggle Leaderboard ranking is similar, with the following differences:

- **click_id**: reference for making predictions

**Target Variable**
- **is_attributed**: the target that is to be predicted, indicating the app was downloaded
(not included in the test data for Kaggle Leaderboard ranking)

### Important resource
- anormaly detection: https://www.youtube.com/watch?v=086OcT-5DYI
- Learning from imbalanced data: https://www.jeremyjordan.me/imbalanced-data/
