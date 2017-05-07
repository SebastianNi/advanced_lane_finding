In the folder are all the processed calibartion and test images
---
General format:
* `filename.png`							    <-- Original image
* `filename_01_undistorted.png`				    <-- Undistorted image
* `filename_01_undistorted_with_polygon.png`    <-- Undistorted image with the polygon drawn where the lane it roughly expected
* `filename_02_warped.png`					    <-- Warped image cutout
* `filename_03_binarized.png`					<-- Binarized image
* `filename_04_binarized_warped.png`			<-- Binarized warped image
* `filename_05_warped_windows.png`			    <-- Warped (binarized) image with sliding windows drawn to show the found lines
* `filename_06_warped_result.png`				<-- Warped (binarized) result with lane drawn
* `filename_07_result.png`					    <-- Original undistorted image with lane drawn