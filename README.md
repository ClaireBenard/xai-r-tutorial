# Introduction

This tutorial illustrates the use of explainable AI techniques (XAI) on text data. 
The data used is open data from Kaggle, you can download the raw data 
[here](https://ai.stanford.edu/~amaas/data/sentiment/)

It contains 3 columns: `id`, `reviews` and `sentiment` and 50,000 rows but to make 
things faster and simpler, I take a random sample of 12,000 reviews for this tutorial.


# Requirements

This tutorial uses the following R packages:

* tidyverse
* stringr
* textrecipes
* tidymodels
* randomForest
* DALEXtra

# Running the code

1. Unzip the imdb data, named `imdb_dataset.csv.zip` in the `data` folder
2. Open the notebook `2023-02-03-cb-xai-r-tutorial.Rmd` that contains the code for the tutorial
3. Run the notebook :)

The file `2023-02-03-cb-xai-r-tutorial.md` is the github document that you can open 
[here](https://github.com/ClaireBenard/xai-r-tutorial/blob/main/2023-02-03-cb-xai-r-tutorial.md) 
for more comfortable reading. The folder `2023-02-03-cb-xai-r-tutorial_files` contains
the images of the visuals created in the notebook.
