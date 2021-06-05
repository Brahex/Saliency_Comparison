# Saliency Comparison

The code used for my bachelor thesis.

If you want to run it yourself here are the three required steps:

- Clone https://github.com/iFede94/ArtDL from Federico Milani and Piero Fraternali for their Convolutional Model for Iconography Classification in Paintings.
- Add their [ArtDL dataset](https://drive.google.com/file/d/16FK1YnHPhGqCHf_EpovzcH0v90yXcCer/view) to the same folder (only if you intend to create your own image subsets, do comparison calculations, or simply want acces to other test images. Not necesary to run the simple example.)
- Add the files from this repo to the same main folder, replacing any duplicates.

This repo contains:
- An architecture folder that replaces Federico Milani and Piero Fraternali their architecture folder. The detach in their model structure is removed so the gradients can be calculated backward (a seperate model definition is made for this).
- A saliency folder with all results from my saliency comparison calculations over the entire ArtDL dataset and subsets of it.
- A Comparative analysis jupiter notebook file with the code used to generate the saliency maps and do calculations with the results. After the initial code blocks load all the required data, the next few blocks are an example where visual saliency maps are generated for an input image. The code blocks after that are for creating subsets of the dataset and doing comparison calculations on large groups of images.
