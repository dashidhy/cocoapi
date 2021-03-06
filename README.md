# COCO API 
- http://cocodataset.org/

COCO is a large image dataset designed for object detection, segmentation, person keypoints detection, stuff segmentation, and caption generation. This package provides Matlab, Python, and Lua APIs that assists in loading, parsing, and visualizing the annotations in COCO. Please visit http://cocodataset.org/ for more information on COCO, including for the data, paper, and tutorials. The exact format of the annotations is also described on the COCO website. The Matlab and Python APIs are complete, the Lua API provides only basic functionality.

In addition to this API, please download both the COCO images and annotations in order to run the demos and use the API. Both are available on the project website.
-Please download, unzip, and place the images in: coco/images/
-Please download and place the annotations in: coco/annotations/
For substantially more details on the API please see http://cocodataset.org/#download.

After downloading the images and annotations, run the Matlab, Python, or Lua demos for example usage.

# Install Python API

```bash
cd ./PythonAPI
```

- To install pycocotools locally:
 
```bash
python setup.py build_ext --inplace
rm -rf build
```

- To install pycocotools to the Python site-packages, e.g., to a conda environment:

```bash
python setup.py build_ext install
rm -rf build
```

# Python API Demo

- [Data loading and visualization](https://github.com/dashidhy/cocoapi/blob/master/PythonAPI/pycocoDemo.ipynb)
- [Evaluation](https://github.com/dashidhy/cocoapi/blob/master/PythonAPI/pycocoEvalDemo.ipynb)