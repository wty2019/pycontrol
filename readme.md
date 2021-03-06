## pycontrol


​	Pycontrol is a library that implement vision, control, mathematics, machine learning, deep learning and other aspects from scratch. Adapted the 14 lectures of Gao Xiang slam into Python version. It is the knowledge I summarized in the learning process.


​	This library is very convenient to use, but there may be some bugs, so it can only be used as a learning tool, not applied in engineering. If you encounter something wrong or difficult to understand, please discuss it in the discussion area.

​	The project is in progress, welcome to discuss.



## installation
Installation methods and installation dependencies are [here](https://github.com/wangce888/pycontrol/blob/master/docs/installation.md)



## DOCS
The knowledge of principle can be referred here
[principles](https://github.com/wangce888/pycontrol/blob/master/docs/tutorials)



## examples

### math
[quaternion](https://github.com/wangce888/pycontrol/blob/master/docs/math/quaternion.py)



### matrix

[matrix](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/matrix.py)&emsp; &emsp;[geometry](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/geometry.py)&emsp;&emsp;[Lie group lie algebra](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/lie.py)&emsp;&emsp;[plotTrajectory](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/plotTrajectory.py)&emsp;&emsp;[trajectoryError](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/trajectoryError.py)

![](https://github.com/wangce888/pycontrol/blob/master/docs/matrix/data/trajectory.png)



### cv

* **calib3d**  
[undistortImage](https://github.com/wangce888/pycontrol/blob/master/docs/cv/calib3d/undistortImage.py)&emsp;&emsp;[stereoVision](https://github.com/wangce888/pycontrol/blob/master/docs/cv/calib3d/stereoVision.py)&emsp;&emsp;[jointMap_pangolin](https://github.com/wangce888/pycontrol/blob/master/docs/cv/calib3d/jointMap_pangolin.py)&emsp;&emsp;[jointMap_pcl](https://github.com/wangce888/pycontrol/blob/master/docs/cv/calib3d/jointMap_pcl.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/cv/data/jointMap.png)

* **image_processing**  
[filtering](https://github.com/wangce888/pycontrol/blob/master/docs/cv/image_processing/filtering.py)&emsp;&emsp;

* **features**  
[Harris_corner_detector](https://github.com/wangce888/pycontrol/blob/master/docs/cv/features/Harris_corner_detector.py)&emsp;&emsp;[SIFT_feature_detector](https://github.com/wangce888/pycontrol/blob/master/docs/cv/features/SIFT_feature_detector.py)&emsp;&emsp;[ORB_feature_detector](https://github.com/wangce888/pycontrol/blob/master/docs/cv/features/ORB_feature_detector.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/cv/data/harris.png)
![](https://github.com/wangce888/pycontrol/blob/master/docs/cv/data/orb.png)



### ml

* **clustering**  
[kmeans](https://github.com/wangce888/pycontrol/blob/master/docs/ml/kmeans/kmeans.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/ml/data/kmeans.png)  

* **regression**  
[Least_squares](https://github.com/wangce888/pycontrol/blob/master/docs/ml/Least_squares/Least_squares.py)&emsp;&emsp;[LS_svd](https://github.com/wangce888/pycontrol/blob/master/docs/ml/Least_squares/LS_svd.py)&emsp;&emsp;[LS_fitting_plane](https://github.com/wangce888/pycontrol/blob/master/docs/ml/Least_squares/LS_fitting_plane.py)&emsp;&emsp;[LS_fitting_surface](https://github.com/wangce888/pycontrol/blob/master/docs/ml/Least_squares/LS_fitting_surface.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/ml/data/LS_svd.png)
![](https://github.com/wangce888/pycontrol/blob/master/docs/ml/data/LS_fitting_plane.png)
![](https://github.com/wangce888/pycontrol/blob/master/docs/ml/data/LS_fitting_surface.png)


### dl

[activation](https://github.com/wangce888/pycontrol/blob/master/docs/dl/activation.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/dl/data/activation.png)



### nonlinear optimization

[fitting_curve](https://github.com/wangce888/pycontrol/blob/master/docs/nonlinear_optim/fitting_curve.py)&emsp;&emsp;[fitting_curve_ceres](https://github.com/wangce888/pycontrol/blob/master/docs/nonlinear_optim/fitting_curve_ceres.py)&emsp;&emsp;

![](https://github.com/wangce888/pycontrol/blob/master/docs/nonlinear_optim/data/fitting_curve.png)



### path planning

[Dijkstra](https://github.com/wangce888/pycontrol/blob/master/docs/control/path_planning/Dijkstra.py)

![](https://github.com/wangce888/pycontrol/blob/master/docs/control/path_planning/data/Dijkstra.png)



### data structure

* **graph**  
[Dijkstra](https://github.com/wangce888/pycontrol/blob/master/docs/data_structure/graph/Dijkstra.py)