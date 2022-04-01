# KKR_Spectral_Analysis
Constrained Variational Kramers-Kronig Differential Dielectric Function Analysis of Pump Probe Spectra


This repo contains all the scripts I use to analyse and convert differential transmission and reflection spectra to changes in the complex dielectric function. The details of the analysis are in discussed in our paper 'Extracting quantitative dielectric properties from pump-probe spectroscopy' (https://www.nature.com/articles/s41467-022-29112-y). 

I have assembled the analysis scripts in a Jupyter notebook to facilitate a step-by-step walkthrough of the analysis with all the required code working and written out in full, but this is by no means a commercial code or meant to be ready for immediate 'turn-key' depolyment. That being said, if you are having diffiulty understanding the script or getting it to work, please email me, it would be my pleasure to discuss this with you and improve the code and its usability together. If you have a question you can also comment on the linked notebook here (https://app.reviewnb.com/arjun-ashoka/KKR_Spectral_Analysis/). 

The following Jupyter notebooks with their associated datasets are provided in this repo and span a variery of different measurement samples and experimental geometries: 

1. CsPbBr3 - bifacial film (no Fabry–Pérot resonances included), measured in transient transmission geometry, uses published ellipsometry and transmission spectra to calculate the derivatives (dT/deps)
2. Pentacene - bifacial film (no Fabry–Pérot resonances included), measured in transient transmission geometry, uses published ellipsometry and transmission spectra to calculate the derivatives (dT/deps)
3. MoS2 - 2D material (optically treated as a surface), measured in transient transmission geometry, uses only the transmission spectra to calculate the derivatives (dT/deps)
4. GaAs - wafer, measured in transient reflection geometry, uses only the transmission spectra to calculate the derivatives (dT/deps)

The files of the form 'Constrained Variational KKR - teardown for bear TA Timeslice_($Material$).ipynb' are the Jupyter notebooks and their respective folders contain the data needed to run the scripts. If the whole git is copied as is, the paths should be contained. 
