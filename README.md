Python Suite for High-Pressure Mineral Physics

This suite specifically focuses on automizing the processing of Raman spectra gathered via Raman spectroscopy at
increasing pressures. It takes spectra data from a raw .txt file and transforms it into a visual spectra stack and 
can apply fit models to peaks to generate an accurate wavenumber vs. pressure graph and compare different sample 
data sets.

This library was developed to analyze bridgmanite samples at increasing pressures in a diamond anvil cell. Ramam 
measurements were taken at each pressure step and downloaded in a .txt file.

Required Libraries: numpy, scipy, matplotlib, pandas, lmfit

Set Up Instructions for Windows computer:
1) Download PythonPI (Python 3.14)
2) Open Windows home tab and type 'cmd' into the search bar to open the command window
3) In the command window type the following and press enter after each command to update and download libraries:
      - python -m ensurepip --upgrade
      - pip install numpy
      - pip install scipy
      - pip install matplotlib
      - pip install pandas
      - pip install lmfit
4) Now you should be able to open the IDLE Shell window and start coding

This repository is a work in progress and will be updated when necessary.

