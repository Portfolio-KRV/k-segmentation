# K-segmentation
Developed in the Pattern Recognition in Data Mining course by: Kevin Reyes.
## Objectives
- Segment images using K-Means algorithm.

## Description
Image segmentation with K-Means algorithm.

## Conclusions
- An increase in the quality of the segmented image is noted by increasing the number of clusters, greater detail of the image can be captured through more clusters, however the latter is rarely the objective of segmenting images.
- To obtain an optimal result, for example for an autonomous vehicle to be able to detect important objects on a route, a cluster number should be considered that at least allows detecting essential elements, such as: traffic signs, people, sills, etc. landscape and other vehicles.
- The algorithm can present flaws when some objects in the image have similar colors, since it segments them into the same cluster when they should be different. That is, the algorithm is only considering color information to detect the objects, it does not use spatial or shape information.

## Technology stack
- Cv2.
- Numpy.
- Matplotlib.