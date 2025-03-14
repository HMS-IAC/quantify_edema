# How separated are cells in tissue? 
This tutorial teaches how to quantify the extent of cell-cell separation in histopathology tissue. 
Examples shown are on cell-cell separation of inflammed and healthy H&E slices of mouse pancreases.  
This tutorial requires basic familiarity with python.  

# Dependencies 
Install uv following [these](https://docs.astral.sh/uv/getting-started/installation/) instructions. 



## It follows these steps: 
- [Quality control](./0_Quality_ctrl.ipynb)  
- [Segment tissue (forground vs background)](./1_Segment_tissue.ipynb)  
- [Segment gaps between cells in the foreground region](./2_Segment_gaps.ipynb)   
- [Export segmentation masks from QuPath](./3_Export_segmentation.ipynb)  
- [Tile output images](./4_Tile_images_uv.ipynb)  
-- To run: ```uvx juv run 4_Tile_images_uv.ipynb```  
- [Count and export the density of branchpoints](./5_Count_branchpoints_uv.ipynb)  
-- To run: ```uvx juv run 5_Count_branchpoints_uv.ipynb```  
    


## Acknowledgements  
This tutorial heavily builds on QuPath functions  
Bankhead, P. et al. QuPath: Open source software for digital pathology image analysis. Scientific Reports (2017).  
https://doi.org/10.1038/s41598-017-17204-5 

