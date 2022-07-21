# EEG-automate-preprocess
Simple code to automate EEG data preprocessing

This code has been written in the MATLAB environment, using the EEGLAB toolbox, to facilitate working by EEG raw messy data. Using the snippet code, you can be able to adopt a standard approach to clean EEG data and ready for analysis. 

Manipulations that this code does:
    1. Band-pass cut-off filter
    2. Re-referencing (base on PREP Pipeline Algorithm)
    3. Artifact Rejection:
      3.1. Artifact Subspace Reconstruction (ASR) for detecting and removing high-amplitude components (usually raised from muscle movement and sensor motion)
      3.2. Independent Component Analysis (ICA) using ICLabel for removing eye movement artifacts
