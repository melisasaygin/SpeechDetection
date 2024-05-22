# Speech Detection Repository
Speech production confounds many psychophysiological parameters and can disrupt the true associations between psychosocial constructs and physiological reactivity. This repository ıs intended for use by ambulatory psychophysiology researchers, and contains the following: 1.machine learning analysis scripts used in the associated paper for training, validating, and comparing between speech detection methods, 2.final best models deployed for speech activity detection along with their feature extraction scripts. Example daily life data will be added in future. See the following paper (to be added upon publication) and pre-registration (https://osf.io/bk9nf) for further description of utilization.

The abbreviations in this repository are

"Acc" refers to the method of accelerometers positioned on the upper sternum

"2 bands RIP" refers to the method with two respiratory inductance plethysmography (RIP) bands (one at thorax and one at abdomen)

"Thorax RIP" refers to the method using only the thorax belt features of RIP

"ImP" refers to the method of across-thorax impedance. This was both measured and validated for two different devices, hence the variations ImP 5fs (as measured by the VU-AMS 5fs device) and ImP Core (as measured by the VU-AMS Core device, successor of 5fs)

The document including detailed instructions on the repository structure and how to implement the models to your data will be added upon publication.

NOTE: If you cannot preview a .ipynb (notebook) file at a given time, this is likely a github related bug. Then, go to https://nbviewer.jupyter.org/ and paste the URL there to preview a document with its output. (Or, you can download the script file with the associated dataset and run it on your computer).
