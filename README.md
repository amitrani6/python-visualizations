# python-visualizations
Sample visualizations produced with Python libraries

This repository contains three files and one folder:

1) `supporting_files/` - A folder containing data used to create the visualizations

2) **.gitignore** - Contains the files excluded from this repository

3) **OHLC_Chart_Python_Package_Comparison.ipynb** - A jupyter notebook containing OHLC and growth percentage visualizations

4) **README.md** - This document


# OHLC

The open-high-low-close (OHLC) chart depicts the various price ranges of a security over time. An average price can be derived from the OHLC chart which can then be used to compare the growth of the security to an index.

Panda's `.pct_change()` method can be used to derive growth from period to period entries in a data frame.
