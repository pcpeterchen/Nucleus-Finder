# Nucleus-Finder
Connectomics project written for Summer Undergraduate Research Experience 2015(SURI) at WVU-SNRC.  
The goal is to find nuclei from a mask of connectomic data after the raw data has been put through Ilastik pixel classification.
Finder.py finds the centers of all the nuclei and Cropper.py crops the corresponding cell bodies into individual .tiff stacks for Ilastik carving.
Viewer.py allows for quick viewing of the results after Cropper.py has run.  
confmat.py is a confusion matrix maker for the PeteSURIposter.pdf, which is a poster made for the completion of the SURI internship
