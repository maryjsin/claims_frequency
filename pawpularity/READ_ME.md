# Petfinder's.my Pawpularity Contest on Kaggle

They say a picture is worth a thousand words, for this project, we try to determine what makes a good picture for the adoption profile of animals in shelters. To increase adoption rates, this project uses a convolutional neural network trained on thousands of pet images and tabular metadata. The model uses image data augmentation techniques to get more accurate predictions and an exponential decay learning rate schedule to speed up the model training process. 

This project uses raw images and metadata from Kaggle to predict the "Pawpularity" of pet photos. The model was trained and tested using PetFinder.my's thousands of pet profiles.

### How Pawpularity Score Is Derived
The Pawpularity Score is derived from each pet profile's page view statistics at the listing pages, using an algorithm that normalizes the traffic data across different pages, platforms (web & mobile) and various metrics.
Duplicate clicks, crawler bot accesses and sponsored profiles are excluded from the analysis.

Link to Kaggle: https://www.kaggle.com/competitions/petfinder-pawpularity-score
