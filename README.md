# cocoapi

This is a fork of [cocoapi](https://github.com/cocodataset/cocoapi) contains change to fix following error:

AttributeError: module `numpy` has no attribute `float`.
np.float was a deprecated alias for the builtin float. To avoid this error in existing code, use float by itself. Doing this will not modify any behavior and is safe. If you specifically wanted the numpy scalar type, use np.float64 here.

