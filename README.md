# Graphene-Raman-Mathematica
A set of Mathematica programmes for fitting Raman spectra and maps of graphene

The following programmes are designed for the analysis of CVD graphene but may be easily altered to analyse maps of exfoliated graphene and other materials such as dyes, etc. 

### Motivation
Raman maps can contain thousands of spectra with varying backgrounds and peaks. Commercial software packages such as Origin are often unsuitable or inefficient for graphing such maps. 
This programme is much faster than any commercial programmes I have seen, which is very beneficial when analysing maps of numerous samples.

### Features
* Fits the D, G, and 2D peaks with Lorentzian functions, as well as the D+D" and strained 2D peak when present.
Exports each fitted spectrum as a .png file.

<img src=https://cloud.githubusercontent.com/assets/12942120/8439620/7c09f818-1f6d-11e5-9af2-f893413cf6e7.png width=440 height=300/>


* Performs analysis such as identifying multilayer and strained areas, then exports 2D and 3D images.

<img src=https://cloud.githubusercontent.com/assets/12942120/8439617/7bfa54bc-1f6d-11e5-9e13-5acf6d03de72.PNG width=350 height=350/>
<img src=https://cloud.githubusercontent.com/assets/12942120/8439618/7c01a5fa-1f6d-11e5-9f80-0ab5292c3f91.PNG width=500 height=350/>

* Exports fitted histograms of the average G peak area (and enhancement factor where applicable).
<img src=https://cloud.githubusercontent.com/assets/12942120/8439619/7c0612c0-1f6d-11e5-9489-907ea716b2b7.png width=470 height=350/>

Please read the guide "Analysing Raman maps of graphene with Mathematica" for details on the functionality of the programme and how to edit it. 


### Programmes
* __Main__ __Raman__ __map__ __fitting__ __programme:__ The main programme
* __map,__ __histogram__ __plotting__ __programme:__ A programme for generating new histograms and map images with different scales, titles, etc.
* __Normalization__ __programme:__ A programme for importing a set of spectra and multiplying the intensities by a normalization factor.
* __Single__ __plot__ __checker:__ A programme for fitting a single spectrum. Numerous images are returned, allowing the user to check programme parameters and individual peak fits.
