# Head_Pose_3d
#initial


## Topics
- face detection
- keypoints detection
- 3d face alignement
  - define generic 3d face model 
  - cv2 solve PnP

## TODO
- [ ] implement webcam loop
  - grab frame 
  - do something
  - break on key pressed Esc

- [ ] detect face
  - download model
  - prepare input
  - predict
  - draw bbox on frame
- [ ] detect 2d facial landmarks
  - download model
  - detect keypoints
  - draw markers on frame
- [ ] 3d face alignment
  - perform camera calibration with checkerboard
  - store intrinsics
  - get generic 3d face model
  - solve PnP with 3d face and detected 2d keypoints
  - visualize head pose on frame
  - visualize 3d head pose
