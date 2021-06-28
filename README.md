# SARBuD
SARBuD (SAR Building Dataset) is a medium-high resolution SAR building dataset for deep learning. 
The dataset was acquired from SAR images. 
It includes building patches of SAR image and corresponding label images which are interpreted manually with high resolution optical images. 
The SARBuD dataset contains building areas with different terrain scene types, different distribution types, and different regions.
It can support researchers to conduct building SAR image feature analysis and provide training and test data for deep learning. 
Based on SARBuD dataset, researchers can carry out researches on semantic segmentation and extraction of building areas.

The image patches are derived from 10m resolution SAR image, sizes of one patch is 256*256 pixels. 
There are about 25000 SAR image patches of building area and corresponding 25000 labeled binary images in current version. 
More image patches will be added later. 

**Besides, our dataset is so large that you cannot download it direcly, 
we start LFS service for it and you need to install lfs for your computer and download the dataset 
by command like "git lfs clone https://github.com/CAESAR-Radi/SARBuD.git". 
Maybe sometimes, bandwidth of our lfs runs out in current month and you can't download it, then it will reset in next month.**
