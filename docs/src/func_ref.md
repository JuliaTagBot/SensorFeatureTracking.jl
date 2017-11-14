## Function Reference

```@contents
Pages = [
    "func_ref.md"
]
Depth = 3
```
### Common
```@docs
drawfeatureLine!
drawfeatureX!
getApproxBestHarrisInWindow
getApproxBestShiTomasi
```
### Block Matching Feature Tracking
```@docs
compute_sad
compute_ssd
compute_ncc
block_tracker!
```

### KLT Feature Tracking
Forward KLT tracking with pyramids
```@docs
ImageTrackerSetup
trackOneFeature
KTL_Tracker!
trackOneFeaturePyramid
warpping!
```

### Camera Models and Geometry
```@docs
CameraModelandParameters
CameraModel
```

### Inertial Sensor Aided Feature Tracking
```@docs
IMU_DATA
estimateRotationFromKeypoints
predictHomographyIMU!
integrateGyroBetweenFrames!
HornAbsoluteOrientation
```

## Index
```@index
```