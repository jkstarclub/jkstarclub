# Welcome

I am AeroReady ✨
[Convocation](https://youtu.be/OpY1wS1aBok)
[PDF](https://issuu.com/bcit/docs/4488_convo_digital_program_isuu/32)

Also, NFL ready ::
ssh -N -f -L localhost:8889:localhost:8889 user@jupyter-ip-address

## Checklist ⚡

Here are some links to get things started:

1. AM32
    https://github.com/AlkaMotors/AM32-MultiRotor-ESC-firmware/
2. Headtrack
    https://github.com/dlktdr/HeadTracker/
3. Udacidrone
    https://github.com/udacity/udacidrone/
4. Crazyfile
    https://github.com/udacity/FCND-Controls-Crazyflie/
5. Programming Microcontrollers
    STM32F769I-DISCOVERY
    STM32F7508-DISCOVERY
    STM32H750B-DISCOVERY
    STM32L4R9I-DISCOVERY
    STM32L4R9I-EVAL
    STM32F469I-DISCOVERY
6. The Castle
    https://antofthy.gitlab.io/

## System Requirements ⚡

CMake 3.17: https://cmake.org/download/
MSVC v142: https://visualstudio.microsoft.com/visual-cpp-build-tools/

```

feat. micro refinements

In a few days, you will be able to:

 - package content
 - build process
 - refine components
 - do asset management
 - let style control

If there is a track, curve the turn like so: 

Revolve: #123

```

Motion Model: \\ ${X}_{k} = f({X}_{k-1}, {u}_{k}) + {W_k}$ \\
Observation Model: \\ ${Z}_{k} = {h}({X}_{k}) + {V}_{k}$ \\
Initialization: \\ $\hat{x}_{0} = {x}_{0}$, and ${P}_{0} = {P}_{init}$. \\
Prediction: \\ $\hat{x}_{k,k-1} = {f}(\hat{x}_{k-1},{u}_{k}).$ \\
The predicted covariance: \\ ${P}_{k,k-1} = \nabla{f}{P}_{k-1}\nabla{f}^{T}+{Q}_{k}$ \\
The predicted observation value at time k: \\ $\hat{z}_{k,k-1} = {h}(\hat{x}_{k,k-1})$ \\
Observation-Update: \\ $[\hat{x}_{k}] = [\hat{x}_{k,k-1}] + K[{z}_{k} - h(\hat{x}_{k,k-1})]$, \\
${P}_{k} = {P}_{k,k-1} - {K}{S}_{k}{K}^{T}$ \\
where: \\
${S}_{k}$ \\
${K}$ \\
where $\nabla{h}$ is Jacobian Matrix. ${RV}_{k}$ The Covariance\\

${SIFT}{SURF}{HOG}{HoughTransform}{RANSAC}{KalmanFilter}{KF}{EKF}{UKF}{PointCloudLibrary}{ParticleAlgorithm}{Voxels}$
${Scale Invariant Feature Transform}$
the scale space of images and extract the local extrema with Difference of Gaussian function
${Speeded Up RobuFeatures}$
the eterminant of Hessian blob detector / Euclidean distance
${Histogram of Oriented Gradients}$
feature extraction in local region by tracking orientation histograms of edge intensity
${random Hog LPB SURF BRIEF VLC SIFT}{VLC+LBP}$
Hough transform feature extraction technique
${Random Sample Consensus}$
an iterative method to estimate parameters of a mathematical model from a set of observed data that contains outliers / the goal is to determine the points in the space that project onto an image into a set of landmarks with known locations

# Kalman Filter Family
MEKF 'Car Park Dataset' 'Victoria Park Dataset' non linear SLAM.
EKF The predicted observation value at time k is formulated like so where h is Jacobian matrix . R is the covariance of V.
UKF a set of weighted sigma points are used to represent the stochastic characteristics of the state vector.
IKF Iterated Kalman Filter
Mean Slope

