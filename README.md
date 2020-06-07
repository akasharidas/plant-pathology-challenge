# Plant Pathology Challenge

This notebook was originally published as a [Kaggle kernel](https://www.kaggle.com/akasharidas/plant-pathology-2020-in-pytorch). It went on to be one of the top public kernels published for this competition.

With this notebook as a starting point, I finished **83rd** in this competition, out of **1317 teams**. My team consisted of me.

## Competition Problem Statement

Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection. 

The objective of the Plant Pathology Challenge are to train a model to accurately classify an image into different diseased categories or a healthy leaf.

## How to Run

It is recommended to run this in a Kaggle notebook environment.
1. Add [this dataset](https://www.kaggle.com/dataset/cbf0d20bb9deea2b794018659843387bd18e2a8638fae654e996c2b660cfdffb) to your environment. _Note: This is a modified version of the official competition dataset, which is pre-resized to 545x545 and stored as NumPy arrays (.npy) for fast reading._
2. Add the official [competition dataset](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data) to the notebook to access `train.csv` and `test.csv`
3. Turn on GPU (you get 30 hours for free per week).