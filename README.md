# Wrangle and Analyse Data
This project gathers dog ratings tweet data from multiple sources and documents the cleaning procedure using Jupyter Notebook.

Twitter-archive-enhanced.csv is the archive containing tweet data. Wrangle_act.ipynb is the Jupyter Notebook which gathers missing tweet data using the twitter API. API keys are required to run this portion of the code and to gather this data but the resulting data is saved in the tweet_json.txt file. Image-predictions.tsv contains the image predictions for the dog breeds. Act_report.html and wrangle_report.html summarise the cleaning procedures and the insights. These two files can be opened with any web browsers.


## Installation

To run Wrangle_act.ipynb locally Python 3 and Jupyer Notebook both need to be installed. Anaconda will install both.

Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers at https://www.anaconda.com/download/ and the installation instructions [here](https://docs.anaconda.com/anaconda/install/).

Once Anaconda is installed update all the packages. This can be done by running the following code in the Anaconda Prompt:

```
conda upgrade --all
```

Clone the GitHub repository and open the notebook.

```
git clone https://github.com/ezeahunanya/wrangle-and-analyse-data.git
