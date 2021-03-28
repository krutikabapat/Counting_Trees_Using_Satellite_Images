# Counting_Trees_Using_Satellite_Images
Count the number of trees using satellite Images with U-Net

## Important Geo-Spatial Datasets  
1. Border Fence Mexico (https://data.world/carlvlewis/border-fence-boundaries-u-s-mexico)  
2. Parking Areas GIS Data (https://data.world/city-of-bloomington/7a2ba4e7-9479-45ef-8661-08b1d7904d47)  
3. Land Boundry Changes Dataset (https://data.world/dcopendata/2e82614b45de4019b71c97619d95460d-60)    


## Important Libraries specific to geo-spatial dataset for .tif/.tiff files
1. Rasterio (https://anaconda.org/conda-forge/rasterio)  
2. Tifffle (https://anaconda.org/conda-forge/tifffile)  
3. Pillow  (https://anaconda.org/anaconda/pillow)  
4. DetecTree  (https://deepforest.readthedocs.io/en/latest/)


## Methodologies for Tree Count Using Aerial Images   
1. U-Net Based Technique (https://arxiv.org/abs/1505.04597)  
2. Deep Forest(https://github.com/weecology/DeepForest)  
3. Hybrid method involving Faster R-CNN, RolPool, RPN, Softmax (https://paperswithcode.com/paper/deep-learning-based-automated-palm-tree)  

## Implementation Details  

### 1. Results with U-Net for Tree Count  
![ScreenShot](https://github.com/krutikabapat/Counting_Trees_Using_Satellite_Images/blob/main/Results/6.png)  
### 2. Results with Deep Forest for Tree Count    
### 3. Results with Hybrid Model for Tree Count   

## Common Errors and scope for improvement   

1. Common errors while using DeepForest Library (https://deepforest.readthedocs.io/en/latest/FAQ.html#the-plotted-image-looks-wrong-the-trees-are-blue)  
2. Counting of trees using CSR-Net with different dilation rates (https://arxiv.org/abs/1802.10062).    


