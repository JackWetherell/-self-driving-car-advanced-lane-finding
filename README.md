# Advanced Lane Finding

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

In this project, the goal is to write a software pipeline to identify curved lane boundaries in a video.

![Demo](./demo.gif)

## Requirements

- `numpy`
- `scipy`
- `matplotlib`
- `opencv`
- `jupyterlab`

## Usage
To run the pipeline simply launch and run the notebook:

`jupyter lab`

## Directory structure
```
|-- demo.gif                            -> Demo of the pipeline.
|-- advanced_lane_finding.ipynb         -> Notebook containing all code and results.
|-- advanced_lane_finding.pdf           -> Print out of the notebook containing all code and results.
|-- camera_cal                          -> Directory containing camera calibration images.
|-- output_images                       -> Output images at various stages of the pipeline.
|-- test_images                         -> Images to test pipeline.
|-- project_video.mp4                   -> Test video.
|-- project_video_output.mp4            -> Pipeline applied to test video.
|-- project_video_output_outliers.mp4   -> Pipeline applied to test video before fix.
`-- writeup                             -> Write up of the method, results and discussion.
```