# Augmentation_EEGLAB_dataset
This repository focuses on Augmenting EEGLAB dataset to improve Autism spectrum disorder(ASD) identification

# Dataset:
EEG Data for "Electrophysiological signatures of brain aging in autism spectrum disorder"
The study collected data from 28 participants diagnosed with autism spectrum disorder and 28 neurotypical control subjects ranging in age from 18 to 68 years. The experimental protocol involved a 2.5 minute (150 seconds) eyes-closed resting state.

link : https://orda.shef.ac.uk/articles/dataset/EEG_Data_for_Electrophysiological_signatures_of_brain_aging_in_autism_spectrum_disorder_/16840351?file=31351417

This process is divided into two components: data preparation and sample enhancement techniques.

# Part 1:

Implement signal filtering through bandpass and data smoothing operations prior to window segmentation and window-based energy computation.

# Part 2:

Split the dataset into training (90%) and testing (10%) portions.

Enhance the training samples using 5 distinct augmentation strategies and test performance against test samples.
