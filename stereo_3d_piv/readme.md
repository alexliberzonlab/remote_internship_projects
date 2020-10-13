# Stereoscopic and 3D OpenPIV version

The idea is to take 3D calibration from OpenPTV www.openptv.net and add it to OpenPIV-Python https://github.com/openpiv/openpiv-python. 
The main advantage of the OpenPIV calibration is that it provides the solution for air-glass-liquid interfaces and actually for a large set of real PIV experiments


## StereoPIV - background

http://research.me.udel.edu/~prasad/papers/expfl_stereo_review.pdf


## OpenPIV 

http://www.openpiv.net
https://github.com/openpiv/openpiv-python


## OpenPTV
https://www.openptv.net
https://github.com/openptv/openptv
https://github.com/openptv/pyptv


## The idea

1. perform OpenPIV analysis on each frame independently (Left, Right)
2. Use OpenPTV stereo-calibration method to get stereoscopic orientation of the two cameras
3. Wrap the two 2D PIV results onto a single grid using stereoscopic orientaiton using the method of Prasad (see above the background)


## Software

create a repository that demonstrates the operation and think how to make a single GUI or command line set of functions that perform the workflow automatically. 



