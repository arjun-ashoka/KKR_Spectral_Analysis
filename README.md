# KKR_Spectral_Analysis
Constrained Variational Kramers-Kronig Differential Dielectric Function Analysis of Pump Probe Spectra


This repo contains all the scripts I use to analyse and convert differential transmission and reflection spectra to changes in the complex dielectric function. The details of the analysis are in detailed in our paper 'Extracting quantitative dielectric properties from pump-probe spectroscopy' (https://www.nature.com/articles/s41467-022-29112-y). 


I have assembled the analysis in a Jupyter notebook to facilitate a more step by step walkthrough of the analysis technique with all the requited code working and written out in full, but this is by no means a commercial code or meant to be ready for immediate 'turn-key' depolyment. That being said, if you'd like to use it and are having diffiulty understanding the script, please email me, it would be my pleasure to discuss this with you and improve upon it together. 

Jupyter notebooks with associated datasets are provided in this rep with following variery of different measurement samples and experimental geometries : 

1. CsPbBr3 - bifacial film (no Fabry–Pérot resonances included), measured in transient transmission geometry, uses published ellipsometry and transmission spectra to calculate the derivatives (dT/deps)
2. MoS2 - 2D material (optically treated as a surface), measured in transient transmission geometry, uses only the transmission spectra to calculate the derivatives (dT/deps)
3. GaAs - wafer, measured in transient reflection geometry, uses only the transmission spectra to calculate the derivatives (dT/deps)
