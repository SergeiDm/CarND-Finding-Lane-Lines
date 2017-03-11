# CarND-P1-Finding-Lane-Lines
## Project Description

The goal of the project is to detect lane lines on a road. The pipeline consists of the following steps:
- Grayscale conversion.
- Gaussian smoothing.
- Edge detecting by using Canny algorithm.
- Calculating region of interest.
- Line detecting by using Hough transforming.
- Picturing the lane lines.

## Project files

The project includes the following files:
- solidWhiteRight.mp4 – the video to test pipeline.
- white_output.mp4 - the result of pipeline work on 'solidWhiteRight.mp4'.
- solidYellowLeft.mp4 – the video to test pipeline.
- yellow_output.mp4 - the result of pipeline work on 'solidYellowLeft.mp4'.
- challenge.mp4 – the video to test pipeline.
- challenge_output.mp4 - the result of pipeline work on 'challenge.mp4'.
- Finding_Lane_Lines_Solution.ipynb - the script with pipeline.
