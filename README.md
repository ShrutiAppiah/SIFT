# SIFT 

## Paper & associated research
Read the <a href="https://github.com/ShrutiAppiah/SIFT/blob/master/Methods%20for%20Improving%20SIFT.pdf">associated paper on Methods to improve SIFT</a>

## Goal
Scale invariant feature transform for image processing. This is an investigation of methods to improve SIFT algorithms.

## Execution strategy
1. Images are first transformed into a collection of vectors. 
2. Keypoints (of high contrast) for distinguishing features in the image are identified and stored in a DB
3. Some unstable points can falsely record as keypoints. We avoid this using <b> keypoint localization </b> 
4. The resulting feature vector is denoised. It's much smaller and more accurate.

## Results

### Feature detection
<div>
		<img  width="300px" src="img/fd.png" alt="feature detection">
		<br>
		<br>
</div>
	
### Keypoint localization
<div>
		<img width="300px" src="img/kl.png" alt="keypoint localization">
		<br>
		<br>
</div>

## Learnings
Keypoint localization eliminated a significant amount of noise. Varying the image's contrast produced more accurate results, even with keypoint localization.

## Contributors

Shruti Appiah, Mira Sleiman

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright © 2017 Shruti Appiah
