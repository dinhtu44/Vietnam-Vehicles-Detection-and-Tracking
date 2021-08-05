How to Train Detectron2 on Custom Objects
This tutorial implements the new Detectron2 Library by facebook. This notebook shows training on your own custom objects for object detection.

It is worth noting that the Detectron2 library goes far beyond object detection, supporting semantic segmentation, keypoint detection, mask, and densepose.

Accompanying Blog Post
We recommend that you follow along in this notebook while reading the blog post on how to train Detectron2, concurrently.

Steps Covered in this Tutorial
In this tutorial, we will walk through the steps required to train Detectron2 on your custom objects. We use a public blood cell detection dataset, which is open source and free to use. You can also use this notebook on your own data.

To train our detector we take the following steps:

-Install Detectron2 dependencies
-Download custom Detectron2 object detection data
-Visualize Detectron2 training data
-Write our Detectron2 Training configuration
-Run Detectron2 training
-Evaluate Detectron2 performance
-Run Detectron2 inference on test images