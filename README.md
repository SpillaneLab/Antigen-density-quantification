# Antigen density quantification
Fiji macros to quantify antigen density.
# Overview  
Antigen density impacts the B cell response (Fleire et al., 2006) and must be controlled during experiments. Approximate antigen density is calculated using the method described by Galush et al., 2008 (Galush et al., 2008) and is summarized in our Methods Chapter (McArthur, Bajur & Spillane). 

Acquire a minimum of 36 images using the same imaging conditions for both sample (antigen) and lipid to determine the correction factor. Also, acquire a minimum of 36 images of antigen on an antigen-presenting substrate using the same laser power as for the calibration curve. Maintain mean antigen fluorescence intensity within ± 30% on experiment day and across technical repeats to maintain antigen density. 

Macros get the mean fluorescence intensity for the sample and lipid to be used to determine the correction factor, as well as the mean fluorescence intensity of antigen on an antigen-presenting substrate. 
# Installation 
Analysis performed using Fiji (Schindelin et al., 2012). 
1.	Copy the code (from browser or download as .txt) and paste into macro window as: 
     Plugins > New > Macro
2.	Ensure the language is set to IJ1 Macro in the Language tab of the Macro window. 
3.	Save the macro using .ijm extension. 
# Authors
Hannah McArthur – macros and description. 
# References 
Fleire, S.J., Goldman, J.P., Carrasco, Y.R., Weber, M., Bray, D., Batista, F.D., 2006. B Cell Ligand Discrimination Through a Spreading and Contraction Response. Science 312, 738–741. https://doi.org/10.1126/science.1123940
Galush, W.J., Nye, J.A., Groves, J.T., 2008. Quantitative Fluorescence Microscopy Using Supported Lipid Bilayer Standards. Biophys. J. 95, 2512–2519. https://doi.org/10.1529/biophysj.108.131540
Schindelin, J., Arganda-Carreras, I., Frise, E., Kaynig, V., Longair, M., Pietzsch, T., Preibisch, S., Rueden, C., Saalfeld, S., Schmid, B., Tinevez, J.-Y., White, D.J., Hartenstein, V., Eliceiri, K., Tomancak, P., Cardona, A., 2012. Fiji: an open-source platform for biological-image analysis. Nat. Methods 9, 676–682. https://doi.org/10.1038/nmeth.2019
McArthur, Bajur & Spillane – in progress. Once published, reference will go here. 
