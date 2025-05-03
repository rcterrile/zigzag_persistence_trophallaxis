# zigzag_persistence_trophallaxis

This project investigates the use of zigzag persistence on point cloud data generated from honeybee aggregations during food exchange as described in the paper _A computational topology-based spatiotemporal analysis technique for honeybee aggregation_. All work is compiled in a jupyter notebook which may serve as a guide for using dionysus's zigzag methods. 

A sample data folder is included with 2 example frames from the original data and point_clouds.txt which includes all point cloud data from one experiment, which can be loaded into the notebook using the following code:

```
point_clouds = read_point_cloud_file("[path-to-txt-file]")
```

## Dependencies:

For image loading and point cloud generation:
- PIL -> Image
- glob
- cv2
- skimage.filters -> threshold_minimum

For zigzag persistence:
- Dionysus2 -> for its implementation of zigzag persistence

Numerical/plotting/other:
- numpy
- matplotlib.pyplot
- tqdm
