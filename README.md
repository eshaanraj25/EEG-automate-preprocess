# EEG-automate-preprocess
Simple code to automate EEG data preprocessing

This code has been written in the MATLAB environment, using the EEGLAB toolbox, to facilitate working by EEG raw messy data. Using the snippet code, you can be able to adopt a standard approach to clean EEG data and ready for analysis. <br/>

Manipulations that this code does:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;1. Band-pass cut-off filter<br/>
&nbsp;&nbsp;&nbsp;&nbsp;2. Re-referencing (base on PREP Pipeline Algorithm[[1]](#1))<br/>
&nbsp;&nbsp;&nbsp;&nbsp;3. Artifact Rejection:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1. Artifact Subspace Reconstruction (ASR)[[2]](#2) for detecting and removing high-amplitude components (usually raised from muscle movement and sensor motion)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.2. Independent Component Analysis (ICA) using ICLabel[[3]](#3) for removing eye movement artifacts<br/>
      

