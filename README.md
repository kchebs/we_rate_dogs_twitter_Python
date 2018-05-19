# we_rate_dogs_twitter_Python

Since real-world data rarely comes clean, the goal of this project was to first gather data from a variety of sources and in a variety of formats (data extraction), then conduct data munging/wrangling, analysis and visualization. 

I documented my wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python and its libraries. The dataset I wrangled was the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings typically have a denominator of 10, but the numerators are almost always greater than 10. WeRateDogs has over 4 million followers and has received international media coverage.

## Getting Started

To simply view the report, open "Wrangling and Analyzing Twiter.docx." To edit or view the code, open wrangle_act.ipynb.

### Prerequisites

This project requires the Python programming language. You can download and install Python from Python.org. It was constructed using the free Anaconda Jupyter Notebook.

### Installing

Besides installing the necessary programming language, software, and software packages that are imported in the beginning of the code, no other installation is needed.

Python packages that were used are shown below:
* import pandas as pd
* import numpy as np
* import requests
* import json
* import os
* import re
* import matplotlib.pyplot as plt
* import matplotlib.patches as mpatches
* from scipy import stats
* import tweepy  

Tweepy will require a consumer key, consumer secret, access token, and access secret to run. These have been intentionally removed to provide privacy and security.

## File Breakdown

* wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data
* tweet_json.txt: file constructed via Tweepy API
* twitter_archive_master.csv: combined and cleaned data
* twitter-archive-enhanced.csv: file as given
* image-predictions.tsv: file downloaded programmatically
    * The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. 

## Acknowledgments

* Dataset: Twitter.com 
