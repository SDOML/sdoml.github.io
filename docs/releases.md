# SDOML Dataset

*A curated data set from the NASA Solar Dynamics Observatory (SDO) mission in a format suitable for machine-learning research.*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/spaceml-org/helionb-sdoml/blob/main/notebooks/01_sdoml_dataset_2018/sdoml_dataset_colab.ipynb)

## Version 2.0

The SDO ML Dataset (covering 2010 - present) is hosted on the Google Cloud Platform
in the Zarr (`.zarr`) format. SDO/AIA data has been updated to account for a change in calibration after 2019. In addtion to the change in calibration, this updated format includes:

1. FITS header/keyword information (such as observation time, and exposure time).
2. Processes for continually updating the data until the present day.

## Version 1.0

The SDO ML Dataset (covering 2010 - 2018) was originally published as Galvez et al (2019), and is hosted on the Stanford Digital Repository in Numpy's compressed array format (`.npz`).
