# Speech Detection Repository
Speech production confounds many physiological parameters and can disrupt the true associations between psychological variables and physiological reactivity. This repository is mainly intended for use by psychophysiology researchers to implement any of respiratory inductance plethysmography, across-thorax impedance, or upper sternum placed accelerometry data to perform speech activity detection. The repository contains the following: 

a) feature extraction scripts for the different methods

b) machine learning analysis scripts used in the associated paper for training, validating biosignal based speech detection methods

c) script for comparing between the performances of different methods

d) deployed best models for speech activity detection 

Example daily life data may be added in the future. See the following paper (to be added upon publication) and pre-registration (https://osf.io/bk9nf) for further description of use.

The abbreviations in this repository are:

"Acc": refers to the method of accelerometers positioned at the upper sternum (below suprasternal notch)

"2 bands RIP": refers to the method with two respiratory inductance plethysmography (RIP) bands (one at thorax and one at abdomen)

"Thorax RIP": refers to the method using only the thorax belt features of RIP

"ImP": refers to the method of across-thorax impedance, which was measured and validated for two different devices, hence the variations ImP 5fs (as measured by the VU-AMS 5fs device) and ImP Core (as measured by the VU-AMS Core device, successor of 5fs)

The document including detailed instructions on the repository structure and how to implement the models to your data will be added upon publication.

NOTE: If you cannot preview a .ipynb (notebook) file at a given time, this is likely a github related bug. Then, go to https://nbviewer.jupyter.org/ and paste the URL there to preview a document with its output. (Or, you can download the script file with the associated dataset and run it on your computer).
