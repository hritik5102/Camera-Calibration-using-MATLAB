# Camera-Calibration-using-MATLAB
Calibration of the camera using checker-board finding camera parameter using MATLAB


Objective is to find a distance from the camera to the reference object which is fixed.
We use camera calibration app to find a focal length of the camera 
# Characteristics inside the camera 
1) Intrinsic parameter – focal length , lens distortion coefficient , pixel scaling after knowing these parameter we can map real world distance into pixel , improve image quality.

2) Extrinsic parameter – camera’s location in space in relation to fixed object .

3) We take 20-25 images of checkerboard with different orientation and give size of square in mm 
4) We can specify radial distortion coefficient and also compute a tangential distortion when lense and camera sensors are not in parallel 

5) Find the reprojection error – which difference between points detected over the image and points reprojected back into the image using the camera parameter which we just calculated . 

6) We can also apply threshold to get minimum reprojection error and we can visualize from which angle we have taken the images .

7) We change distorted image into undistorted image by removing lens distortion to get optimal result .

8) When you are satisfied with calibration accuracy u can directly Export Camera Parameters or Export Matlab Script.

9) After finding the focal length, move your camera both closer and farther away from the object. Then apply the triangle similarity to    determine the distance of the object to the camera i.e      
	D = (W*F)/P  
	W = object width    
	F = focal length    
	P =  apparent width in pixels

