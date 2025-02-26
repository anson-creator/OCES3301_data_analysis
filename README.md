# OCES 3301 Data Analysis in Ocean Science

NOTE: I happen to be using some data relevant to ocean science, otherwise the "Ocean Science" bit is neither here nor there.

Material mostly in the notebooks. At least three known ways of running these:

1) On your computer, by downloading the pack (there should be a green "code" button near the top right of this page, click it and there should be "download")

2) On your computer, `git clone` this repository. Then you can do `git pull` you get updates (if any). You may or may not want to fork the repository (need a GitHub account), then you can commit changes too.

3) In Google colab, but you will need to pull copies (code and data) to your own Google drive, otherwise changes are not saved.

Clicking the icon below will open a temporary Colab instance, where changes are by default not saved (and you will need to pull the data files with `!wget` commands that are currently commented out in the notebooks). There should be a "copy to drive button" near "file" near the top left for copying to drive.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julianmak/OCES3301_data_analysis/blob/main/) (requires Google login)

### Topics included here

Core topics are

1. some basics of Python, virtual environments, variable types, indexing, plotting
2. (local/remote) reading and manipulating data in python, basics of pandas
3. measure of mismatch, linear regression
4. multi-linear regression, A/BIC, principal component analysis
5. basics of probability, histograms, pdfs, statistical tests
6. more statistical tests, other topics in probability (Shannon / diversity index)
7. time series data, filtering, power spectrum
8. missing data in time, interpolation/extrapolation
9. multi-dimension array data, NetCDF data, xarray, basic plotting, subsetting 
10. maps, interpolation/extrapolation, empiricial orthogonal functions

Extra topics are mostly machine learning oriented, or exploring data repositories (e.g. satellite data from Copernicus)

### Other resources I've found

* [Ryan Abernathey](https://github.com/rabernat)'s [Earth and Environmental Data Science course](https://earth-env-data-science.github.io/intro.html)
* [Python for Environmental Science course](https://github.com/florianjehn/python-for-environmental-science)
* [Data Analysis course from Brian Powell](https://currents.soest.hawaii.edu/ocn_data_analysis/index.html)
* [Methods of Oceanographic data analysis](https://ethan-campbell.github.io/OCEAN_215/) held on [Ethan Campbell](https://ethan-campbell.github.io/)'s GitHub
* [Jonathan Lilly](http://jmlilly.net/)'s [time series course](https://github.com/jonathanlilly/time-series)

### known things to add/check:

* all notebooks to run on Colab with modulo additiongs of `!pip` + will remote load data appropriately

### big updates (18 Jan 2025)

* yaml and environment files added by Jonathan Lee
* default is to load data remotely; to test on Colab (the worst one would be `10` and that seems to run ok)
* added rendered notebooks with intended outputs (in folder `rendered`)
