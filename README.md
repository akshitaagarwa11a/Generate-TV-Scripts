# Generate-TV-Scripts
Udacity DL Nanodegree **TV Script Generation** Project.

## Introduction
In this project, I have generated my own Seinfeld TV scripts using RNNs. I have used a Seinfeld dataset of scripts from 9 seasons. 
The Neural Network I have built generates a new, "fake" TV script.\
Original repo of this project can be found [here](https://github.com/udacity/deep-learning-v2-pytorch), in the `project-tv-script-generation`
folder.

## Results
I have trained a model to give me a loss of about 3.2. You can see that there are multiple characters that say (somewhat) complete 
sentences, but it isn't perfect. It takes quite a while to get good results, and often, you'll have to use a smaller 
vocabulary (and discard uncommon words), or get more data. The Seinfeld dataset is about 3.4 MB, which is big enough for our purposes; 
for script generation you'll want more than 1 MB of text, generally.
