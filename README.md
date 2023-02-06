# MovInt: Model Intent-to-interact in VR
This repository contains the scripts I wrote for my master 2 thesis, these also represent my first programming work.

GOAL: The objective of the study was to model the intent to execute an upper-limb movement. 
We recorded EEG and EMG data then we respectively explored, processed and compute classification metrics with the scripts below.

The work is divided in 3 scripts:

I. Modalities exploration: This accesses to EEG and EMG data to plot the grand-average of each during "idle" and a "pre-move" time frames.

II. Probability: 
-This access the continuous EEG and EMG data stream, extract specific features on time frames of interest then build EEG, EMG and EEG-EMG classifiers for pre-movement classification.
-The script then model the probability of predicting a pre-movement over time
-The built dataframe and classifiers are saves for further analyses and plots.
-Finally, it contains annex processing which compute and plot the accuracy of classifiers built on different time frame as well as the feature weights of each modality.

III. MovInt Metrics: Load the data computed about the previously built classifiers to compute confusion matrices and Receiver operating characteristic

Please contact me if you want to access the data.
