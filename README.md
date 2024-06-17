# Fus-ALS Final Degree Project
This repository includes all the data and scripts in order to perform the single-nuclei RNA analysis for the study. 

The 4 sample files include the files generated by the CellRanger command of 10X.
In the FusdNLS_MyoDicre sample it is included an html file describing the quality of the sequence and a tsne projection regarding the total UMI counts for each cell-barcode and the projection of cells by Clustering. It is an important file in order to know if the flowcell is well sequenced or not. 

There is also two main scripts:

DataAnalysisQC --> An r markdown file to perform the quality control process, the filtering, the normalization as well as the data integration using the CCA and Harmony methods. It is a general preprocessing steps file.

ALSsnRNAseq --> Another r markodwn file with the thorough data clustering analysis, the differential gene expression representations and the complete code for the gene ontology analysis comparing the FusdNLS to the Wild type and the FusdNLS_MyoDicre samples. 
