# bachelor-thesis
This repository contains the python and matlab scripts of the implemented code for the analysis of my bachelor thesis "Exploring effective preprocessing methods of MEG and EEG data for a cognitive fatigue study: A comparative analysis"

SHORT DESCRIPTION OF REPO CONTENT:

Python scripts are jupyter notebooks and can be messy and may contain some errors at some point, due to jumping back into several single parts and access specific plots while writing the text of the thesis. Matlab script are live scripts for implementing DSS model

python script labeled with "QC_..." contain:
- full model setup
- followed by quality control steps
- some plots may not be visible in the output of the notebooks because of matplotlib qt5 backend sometimes using seperate windows

python scripts labeled with "AC_..." contain:
- model setup only for better and faster overview after running model multiple times

python script "dss_eog.ipynb" was the attempt of using meegkit for dss, but failed due to a bug that made some channels have not signal anymore and was the reason why matlab was used instead for eog and ecg artifacts
