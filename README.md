# Antigen density quantification
Fiji macros to quantify antigen density.
# Overview  
Antigen density impacts the B cell response1 and must be controlled during experiments. Approximate antigen density is calculated using the method described by Galush et al., 20082 and is summarized in our Methods Chapter4. 
Acquire a minimum of 36 images using the same imaging conditions for both sample (antigen) and lipid to determine the correction factor. Also, acquire a minimum of 36 images of antigen on an antigen-presenting substrate using the same laser power as for the calibration curve. Maintain mean antigen fluorescence intensity within ± 30% on experiment day and across technical repeats to maintain antigen density. 
Macros get the mean fluorescence intensity for the sample and lipid to be used to determine the correction factor, as well as the mean fluorescence intensity of antigen on an antigen-presenting substrate. 
# Installation 
Analysis performed using Fiji3. 
1.	Copy the code (from browser or download as .txt) and paste into macro window as: 
     Plugins > New > Macro
2.	Ensure the language is set to IJ1 Macro in the Language tab of the Macro window. 
3.	Save the macro using .ijm extension. 
# References 
1.	Fleire, S. J. et al. B Cell Ligand Discrimination Through a Spreading and Contraction Response. Science 312, 738–741 (2006).
2.	Galush, W. J., Nye, J. A. & Groves, J. T. Quantitative Fluorescence Microscopy Using Supported Lipid Bilayer Standards. Biophys. J. 95, 2512–2519 (2008).
3.	Schindelin, J. et al. Fiji: an open-source platform for biological-image analysis. Nat. Methods 9, 676–682 (2012).
4. The description is part of our Methods Chapter which is currently under revision. Once published, the reference will go here. 
