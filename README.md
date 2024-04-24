# K-means Image Segmentation
This project implements the K-means clustering algorithm from scratch for image segmentation.
### K-means Color Only
The norm between the centroid pixel and the current pixel was used as the distance measure. </br>
Pixels were assigned to the cluster based on the lowest score. </br> </br>
![image](https://github.com/XDDz123/k-means-segmentation/assets/20507222/b720c894-a028-43d2-8a1e-f882384402c4)
### K-means Color and Distance
The color difference norm was scaled by the position norm (L2 between pixel positions). </br>
Pixels closer to the cenroid would be favored to have a smaller score. </br> </br>
![image](https://github.com/XDDz123/k-means-segmentation/assets/20507222/d04123dc-fce0-4025-b159-f5d9b46d7fe8)
