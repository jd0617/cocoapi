# cocoapi

This is a fork of [cocoapi](https://github.com/cocodataset/cocoapi) contains change to fix following error:

AttributeError: module `numpy` has no attribute `float`.
np.float was a deprecated alias for the builtin float. To avoid this error in existing code, use float by itself. Doing this will not modify any behavior and is safe. If you specifically wanted the numpy scalar type, use np.float64 here.


# Installation
The installation is similar to the one mentioned in [SimpleBaseline](https://github.com/microsoft/human-pose-estimation.pytorch#installation). 
```
# COCOAPI=/path/to/clone/cocoapi
git clone https://github.com/jd0617/cocoapi.git $COCOAPI
cd $COCOAPI/PythonAPI
# Install into global site-packages
make install
# Alternatively, if you do not have permissions or prefer
# not to install the COCO API into global site-packages
python3 setup.py install --user
```
