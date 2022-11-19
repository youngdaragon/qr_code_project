
qncodedetecter - v1 qncodedetector
==============================

This dataset was exported via roboflow.ai on May 19, 2022 at 9:56 AM GMT

It includes 15 images.
Qncode are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Random rotation of between -34 and +34 degrees
* Random Gaussian blur of between 0 and 0.75 pixels
* Salt and pepper noise was applied to 5 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically


