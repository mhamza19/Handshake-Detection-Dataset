# Handshake-Detection-Dataset
A handshake detection dataset created by scraping publicly available images from Google. Data augmentation and annotation was done using Roboflow. The final dataset includes 4099 images.


Handshake are annotated in YOLO v5 PyTorch format.
The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random exposure adjustment of between -25 and +25 percent
* Salt and pepper noise was applied to 5 percent of pixels

