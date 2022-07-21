# EEG-automate-preprocess
Simple code to automate EEG data preprocessing

This code has been written in the MATLAB environment, using the EEGLAB toolbox, to facilitate working by EEG raw messy data. Using the snippet code, you can be able to adopt a standard approach to clean EEG data and ready for analysis. <br/>

Manipulations that this code does:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;1. Band-pass cut-off filter<br/>
&nbsp;&nbsp;&nbsp;&nbsp;2. Re-referencing (base on PREP Pipeline Algorithm[[1]](#1))<br/>
&nbsp;&nbsp;&nbsp;&nbsp;3. Artifact Rejection:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1. Artifact Subspace Reconstruction (ASR)[[2]](#2) for detecting and removing high-amplitude components (usually raised from muscle movement and sensor motion)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.2. Independent Component Analysis (ICA) using ICLabel[[3]](#3) for removing eye movement artifacts<br/>
      
## References
<a id="1">[1]</a> 
Bigdely-Shamlo, N., Mullen, T., Kothe, C., Su, K. M., & Robbins, K. A. (2015). The PREP pipeline: standardized preprocessing for large-scale EEG analysis. Frontiers in neuroinformatics, 9, 16.<br/>
<a id="2">[2]</a> 
Mullen, T., Kothe, C., Chi, Y. M., Ojeda, A., Kerth, T., Makeig, S., ... & Jung, T. P. (2013, July). Real-time modeling and 3D visualization of source dynamics and connectivity using wearable EEG. In 2013 35th annual international conference of the IEEE engineering in medicine and biology society (EMBC) (pp. 2184-2187). IEEE.<br/>
<a id="3">[3]</a>
Pion-Tonachini, L., Kreutz-Delgado, K., & Makeig, S. (2019). ICLabel: An automated electroencephalographic independent component classifier, dataset, and website. NeuroImage, 198, 181-197.<br/>
