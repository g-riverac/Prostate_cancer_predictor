# Prostate cancer predictor

Prostate cancer predictor throught multiparametric magnetic resonance imaging (MRI).

## Execution order

  1. __Export_dataset.ipynb__: Read files and manage their information in dataframes. Save and export the dataframe using the pickle library.
  2. __Manage_dataset.ipynb__: Load the pickle file with dataset information, then manage and clean the dataset (manage MRI's slices). Save and export the dataframe using the pickle library.
  3. __Training_notebook_all_MRIs.ipynb__: Load the pickle file with clean dataset and train a 3D convolutional neural network (CNN) for each MRI type.
  4. __Test_models.ipynb__: Test the trainen model.

## Dataset

The dataset was obtained from [PROSTATEx challenge](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=23691656)
