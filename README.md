# ISEF 2024 ETSD037 Scout UAV wave and rip current analysis
Python codes for offline analysis of ocean wave flow and rip current.
## Python codes
- `compare_LK_DFD_ECC_area1_r2.ipynb`: Compare optical flow algorithms.
- `process_batch_DFD_info_weight_image_r2.ipynb`: Batch process and produce information-weighted optical flow images by combining DFD and gradient density matrices.
- `process_batch_DFD_r2.ipynb`: Batch process images to produce DFD images and matrices.
- `process_DFD_info_weight_r2.ipynb`: Demonstrate information-weighted optical flow with DFD vectors.
- `rip_current_depth_model_r2.ipynb`: Demonstrate rip channel current analysis using information-weighted optical flow and depth and risk model.
## Image sample folders
- `scout_video_09`: Original image set
- `scout_video_09_gradient_density`: Gradient density as amount of information
- `scout_video_09_info_weighted_wave_flow`: Information-weighted optical flow
- `scout_video_09_rip_current`: Rip channel current analysis with depth and risk model
## Example images
- Original ocean image from 100m
![original ocean image](https://github.com/Cinderpe1t/ISEF_UAV_scout_rip_current/blob/main/scout_video_09/gimbal0_2000.jpg)
- Gradient density to measure information amount
![gradient density as a measure of information amount](https://github.com/Cinderpe1t/ISEF_UAV_scout_rip_current/blob/main/scout_video_09_gradient_density/info_amount_2000.png)
- Information-weighted optical wave flow and rip channel current analysis with depth and risk model
![rip channel current analysis with depth and risk model](https://github.com/Cinderpe1t/ISEF_UAV_scout_rip_current/blob/main/scout_video_09_rip_current/rip5_gimbal0_2000.png)
