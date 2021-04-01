# z0-precisionmeasurement
Precision measurements and tests of the Standard Model using OPAL data at LEP

# Installing with conda

1. Install [anaconda](https://docs.anaconda.com/anaconda/install/) (miniconda probably works too?).
2. `conda env create` reads the `environment.yml` file in this
   repository, creates a new env and installs all necessary packages
   into it.
3. Activate the new env: `conda activate z0-env`
4. Start `jupyter-lab` (or `jupyter-notebook` if you prefer) in the
   environment. This will usually open your browesr automatically. If
   not the link is printed to the console too.


# Git Contents
- Grope_Histograms.ipynb -> Opal visual analysis plots (Grope part of the laboratory)
- opal_data -> Folder where we saved the mc and data root files
- MPL_Model -> Folder where we saved the Machine Learning Model after the Training
- Cuts_by_Hand.ipynb -> Our first approach to the classification of events (physical cuts that were later replaced by the Machine learning algorithm)
- Main_Work.ipynb -> this is the file were we made almost all the task for this laboratory (all the analysis except the grope part and the physical cuts should be here)
- z0_experiment.ipynb ->this is just a leftover from the initial git (should be ignored)