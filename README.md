# Camera-Calibration-using-MATLAB
Calibration of the camera using checker-board finding camera parameter using MATLAB


Objective is to find a distance from the camera to the reference object which is fixed.
We use camera calibration app to find a focal length of the camera 
# Characteristics inside the camera 
1) Intrinsic parameter – focal length , lens distortion coefficient , pixel scaling after knowing these parameter we can map real world distance into pixel , improve image quality.
2) Extrinsic parameter – camera’s location in space in relation to fixed object 
We take 20-25 images of checkerboard with different orientation and give size of square in mm 
We can specify radial distortion coefficient and also compute a tangential distortion when lense and camera sensors are not in parallel then we calibrate 
Find the reprojection error – which difference between points detected over the image and points reprojected back into the image using the camera parameter which we just calculated . 
We can also apply threshold to get minimum reprojection error and we can visualize from which angle we have taken the images .
We change distorted image into undistorted image by removing lens distortion to get optimal result .
