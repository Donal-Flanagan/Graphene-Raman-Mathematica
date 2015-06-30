# Graphene-Raman-Mathematica
A set of Mathematica programmes for fitting Raman spectra and maps of graphene

The following programmes are designed for the analysis of CVD graphene but may be easily altered to analyse maps of exfoliated graphene and other materials such as dyes, etc. 

### Motivation
Raman maps can contain thousands of spectra with varying backgrounds and peaks. Commercial software packages such as Origin are often unsuitable or inefficient for graphing such maps. 
This programme is much faster than any commercial programmes I have seen, which is very beneficial when analysing maps of numerous samples.

### Features
Fits the D, G, and 2D peaks, as well as the D+D" and strained 2D peak when present.
Exports each fitted spectrum as a .png file.

![A typical spectrum of strained CVD graphene](https://github.com/DonalFlanagan/Graphene-Raman-Mathematica/blob/master/Images/Spectrum_map4_1_8.png?raw=true)

Performs analysis such as identifying multilayer and strained areas, then exports 2D and 3D images.
![A 3D image of the area of the G peak from a sample of graphene on nanostructured copper](https://github.com/DonalFlanagan/Graphene-Raman-Mathematica/blob/master/Images/gpeak3.PNG?raw=true)
![A 2D image of the area of the G peak from a sample of graphene on nanostructured copper](https://github.com/DonalFlanagan/Graphene-Raman-Mathematica/blob/master/Images/gpeak1.PNG?raw=true)

Exports fitted histograms of the average (and enhanced) G peak area.
![A histogram of the average G peak area (below a certain cutoff point due to enhancement)](https://github.com/DonalFlanagan/Graphene-Raman-Mathematica/blob/master/Images/histogram.png?raw=true)

Please read the guide "Analysing Raman maps of graphene with Mathematica" for details on the functionality of the programme and how to edit it. 
