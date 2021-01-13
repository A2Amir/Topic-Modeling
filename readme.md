## Introduction

In this repository, I'll use the [gensim](https://radimrehurek.com/gensim/) library to build LDA (Latent Dirichlet Allocation) to classify text in a document to a particular topic.
The [dataset]() I'll use is a list of over one million news headlines published over a period of 15 years. We'll start by loading it from the abcnews-date-text.csv file.

## Hidden Markov Model

To learn more about what the Latent Dirichlet Allocation is and how it works, first watch the videos linked below:

* ![1. Latent Dirichlet Allocation)](/images/1.mp4) 

## Getting Started


 you can download a copy of the project from my GitHub [here](https://github.com/A2Amir/Part-of-Speech-Tagging) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).


0. (Optional) The provided code includes a function for drawing the network graph that depends on [GraphViz](http://www.graphviz.org/). You must manually install the GraphViz executable for your OS before the steps below or the drawing function will not work.

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/A2Amir/Part-of-Speech-Tagging
```

3. Switch to the project folder you cloned the project and create a conda environment (note: you must already have Anaconda installed):
```
$ cd to the project folder you cloned the project
$ conda env create -f hmm-tagger.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
 $ source activate hmm-tagger
 $ jupyter notebook
```

Depending on your system settings, Jupyter will either open a browser window, or the terminal will print a URL with a security token. If the terminal prints a URL, simply copy the URL and paste it into a browser window to load the Jupyter browser. Once you load the Jupyter browser, select the project notebook (HMM tagger.ipynb) and follow the instructions inside to run the tagger.


