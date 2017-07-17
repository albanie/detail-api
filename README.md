## Detail-API Fork

My fork of the Pascal Detail-API, feel free to use. See original README below:

### PASCAL in Detail API

MATLAB and Python API for the [PASCAL in Detail](https://sites.google.com/view/pasd/dataset) multi-task computer vision challenge. This API is a fork of [MS COCO vision challenge API](https://github.com/pdollar/coco).

### To install:
  - For MATLAB, add detail-api/MatlabApi to the Matlab path (OSX/Linux binaries provided)
  - For Python, run "make" and "make install" under detail-api/PythonAPI

### To see a demo:

For **Instance Segmentation and Part Segmentation** tasks, please refer to these demos
  - For MATLAB, run detail-api/MatlabApi/detailPartDemo.m.
  - For Python, run the IPython notebook detail-api/PythonApi/detailPartDemo.ipynb.
  
For **Semantic Segmentation and Object Detection** tasks, please use
  [version 2.2.0 of the API](https://github.com/ccvl/detail-api/releases/tag/v2.2.0), which
  may be downloaded as an archive from the Releases page (see previous link), or fetched
  from Github with the following shell commands: `git clone https://github.com/ccvl/detail-api; git checkout v2.2.0`
  - For MATLAB, run detail-api/MatlabApi/detailDemo.m. 
  - For Python, run the IPython notebook detail-api/PythonApi/detailDemo.ipynb. 
  
