# qRT-PCR

## For selecting the best extraction protocol:
The desire is to fit a kit that saves money, provides high-quality results, and has ease of use. Endogenous controls should provide high-quality repeatable data.  

The kit's user guides are not followed strictly, the same volume of elution buffer is used for more acceptable comparisons.

## Fold changes butterfly plot:
This repository has example data to generate a butterfly plot of log2 fold-changes with two endogenous controls, four sample types, three drug treatments, and one DMSO or negative control. No sample dilutions were necessary for this experiment since the main purpose was to find the Cq values of genes of interest (GOI). TaqMan Assays can be paired for downstream multiplex validation provided this information. 

The treatments used are potential treatment controls, so it is important to determine whether these drug treatments affect the endogenous controls. 

## For multiplex validation: 
Cq values. Singleplex and multiplex reactions should be within one Cq value for each dilution. Use a single threshold across singleplex and multiplex reactions being compared. 

Assay reproducibility. Standard deviations of Cq values greater than 0.5 also could indicate problems with your multiplex reaction and should be examined further. 

Assay linearity. The coefficient of determination (r2) for the fit of the linear regression equation fitted to the semi-log plot should be greater than 0.98 for single and multiplex reactions according to MIQE guidelines. 

Assay sensitivity. The sensitivity is the lowest template concentration at which a Cq value can be reliably determined. Information about the assay sensitivity can be inferred from the lowest data point included in the standard curve with a good fit of the linear regression equation. Sensitivity between multiplex and singleplex reactions should be the same. 

Reaction efficiency. The efficiency for the qPCR assay can be determined from the slope of the linear regression line according to the following equation and is automatically calculated in most software: Efficiency = (10^(–1/slope)–1)*100. Ideally, efficiency should be between 90–110%.
