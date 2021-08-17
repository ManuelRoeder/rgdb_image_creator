# rgdb_image_creator

Requires PIL + Python 3.7 installed

Using the depth map extractor code from https://github.com/designer2k2/depth-map-extractor.
Modified version to create an image that is compatible with HoloPLayStudio RGBD mode.
Supports images taken in Huawei aperture mode.

Usage:
rgbd_image_creator.py input.jpg

Resulting images are places in the "out" folder!


Example input( image taken with Mate 20 pro, aperture mode ):
[IMG_20210117_110909](https://user-images.githubusercontent.com/9356580/129726976-2f059b39-f0f5-42c7-be4a-b21e98d4cdf8.jpg)

Example output:
[input-RGBD](https://user-images.githubusercontent.com/9356580/129727698-d9524dd5-1e9b-470a-aa58-77f980bb9693.JPG)

