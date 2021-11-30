# LombScargle

Introduction: 

This is a toolbox written in Mathematica, providing basic tools to analyse light curve data from surveys.
Currently supported surveys: Catalina, ASAS-SN, ZTF, and NEOWISE.
Please feel free to use, modify, and distribute this toolbox.
Any suggestions to improve the code or bug reports are most welcomed!
If your research work benefits from this toolbox, please cite the web page of this repository: https://github.com/TuanYi/LombScargle. 
Many thanks!



Installation:

In order to run the toolbox, you should have Walfram's Mathematica (version 10 or higher) installed in your computer.
Then you can simply download the repository and put it anywhere on your computer, open the nootbook, and run it.  



Discriptions:

[data]: folder to contain the light curve files. You should put the raw light curve data file in this folder.

[kernel]：modules for data import, LombScargle, and other useful tools.  

[look.nb]: notebook that demonstrate how to use the tools to find the periodicity of a given lightcurve.

[results]: you can export any results you want in this folder 



Example:

Step1: A lightcurve was downloaded from the Catalina Real-Time Transient Surveys:

![lightcurve](https://user-images.githubusercontent.com/81213494/144019936-013bd759-f42a-486c-90b4-3c5c74011d00.jpg)

Step2: Use the toolbox to import the data, find the period of this source by using the generalized Lomb-Scargle algorithm. 
Please refer to the following paper for details of the Lomb-Scargle algorithm:

VanderPlas 2018: https://ui.adsabs.harvard.edu/abs/1982ApJ...263..835S/abstract

Zechmeister & Kürster 2009: https://ui.adsabs.harvard.edu/abs/2009A%26A...496..577Z/abstract

Scargle 1982: https://ui.adsabs.harvard.edu/abs/1982ApJ...263..835S/abstract

Lomb 1976: https://ui.adsabs.harvard.edu/abs/1976Ap%26SS..39..447L/abstract:

(a) the lombscargle power:
![lombscargle_power](https://user-images.githubusercontent.com/81213494/144019954-f9f0487c-49be-4957-914c-d2cc0d3b21bf.jpg)

(b) the phasefolded light curve:
![phased_lightcurve](https://user-images.githubusercontent.com/81213494/144019964-e5962796-1407-40ce-96ae-c1cfe084f91d.jpg)
