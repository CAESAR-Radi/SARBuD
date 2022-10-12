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

To use this dataset, please cite the following papers:
 
1. Wu F, Wang C, Zhang H, Li J, Li L, Chen W, et al. Built-up area mapping in China from GF-3 SAR imagery based on the framework of deep learning. Remote Sensing of Environment. 2021, 262:112515. 
2. Wu F，Zhang H，Wang C，Li L，Li J J，Chen W R and Zhang B. 2022. SARBuD1.0： A SAR Building Dataset Based on GF-3 FSII Imageries for Built-up Area Extraction with Deep Learning Method. National Remote Sensing Bulletin. 2022. 26（4）：620-631.

Please contact us if you have any questions:wufan@aircas.ac.cn(Prof.Wu)
