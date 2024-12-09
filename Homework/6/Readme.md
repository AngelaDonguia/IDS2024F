1. The temperature anomaly in 2050 is 1.523∘C. The quadratic model forecasts a temperature increase by that year.precise would be 1.5226. Because of its exponential expansion, the data's rising provides a more accurate depiction of reality.

2. Epsilon and MinPoints are the two free parameters.
3.  The parameter that was not unique
  unique parameter begin by picking an arbitrary point in our dataset. If there are more than minPoints points within a distance of epsilon from that point, (including the original point itself), we consider all of them to be part of a "cluster" the ability to further increase the high epsilon while also low Minpts.

![image](https://github.com/user-attachments/assets/34ab3fb9-c865-46f0-9d97-c32c53fa84ba)

7.  by reducing the size of  modest epsilon it was more difficult to form a cluster.
     In order to reduce the number of points that qualified for the dense zone, I raised MinPoints to a few points. The outcome is made to be an outlier.
![image](https://github.com/user-attachments/assets/49722934-15b5-4f93-b7a7-e63c0bb79c01)
Since DBSCAN considers the points in an arbitrary order, the middle point can end up in either the left or the right cluster on different runs.DBSCAN is more effective for this dataset.
![image](https://github.com/user-attachments/assets/acbb6a5d-db58-465e-9397-6b752e771df4)

By using a linear x-axis and a logarithmic y-axis, this graphic enables us to see changes spanning multiple orders of magnitude. The trend in the blue, yellow, and red curves' first phase seems to be linear on b denotes how steeply the values increase. The curves.The second phase as they advance, indicating a change to a non-linear pattern.The theories that best explain this behavior are logistic growth and exponential decay toward a maximum, where growth slows as as it gets closer to its peak. The red and yellow curves plateau at steadily lower values, whereas the blue curve reaches the maximum final value. Error bars indicate data variability.
