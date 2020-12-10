# Analyze_Vesicles
This repository contains codes used for analysing segmented membrane structures like vescicles used in Kakanj et.al (manuscript in preparation).
These can be used for :

1. Reshaping and normalising images
  The images are cropped to get an uniform image size across all the experiments

2. Identifyting 'spots/vesicles' using connected components
  Pre-processed images are segmented using Ilastik and Simple Segmentation results are saved. The binary mask thus generated for the vescicle 
  spots are then used individually to identify each spots. Image features like average area and number of spots are then extracted for all such 
  identified spots.
  
3. Iterating on many images and conditions and generating box plots
  Measurements are repeated for all the different experiments and genetic condition. The combined results per experiment are represented in Box plots
  
4. TO DO : Statistical tests 
 
