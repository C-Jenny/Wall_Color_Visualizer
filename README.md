# WALL COLOR VISUALIZER
#### This code makes use of a pre-trained model DeepLab, a segmentation model trained on ADE20K dataset to segment the image. To extract the wall region, segmentation map is pre-processed so that the wall region alone will be changed to white color while the other regions to black color. After extracting the mask, the desired color can be substituted with the help of RGB values and blended with the input image to get a realistic color replaced image with reserving brightness. 
#### ADE20K Dataset - Landmark image segmentation dataset consists of 20K images belonging to outdoor and indoor.The images in the dataset have been categorized into 150 classes.


