# Toygs
This paper presents a Toy-GS method for accurately rendering large-scale free camera trajectories. Specifically, we propose an adaptive spatial division approach for free trajectories to divide cameras
and the sparse point cloud of the entire scene into various
regions according to camera poses. Training each local Gaussian in parallel for each area enables us to concentrate on texture details and minimize GPU memory usage. Next, we use
the multi-view constraint and position-aware point adaptive
control (PPAC) to improve the rendering quality of texture
details. In addition, our regional fusion approach combines
local and global Gaussians to enhance rendering quality with
an increasing number of divided areas. Extensive experiments
have been carried out to confirm the effectiveness and efficiency of Toy-GS, leading to state-of-the-art results on two
public large-scale datasets as well as our SCUTic dataset. Our
proposal demonstrates an enhancement of 1.19 dB in PSNR
and conserves 7 G of GPU memory when compared to various benchmarks.
[![image](https://github.com/Xiaohan-Z/Toygs/blob/main/pipline.png)](https://github.com/Xiaohan-Z/Toygs/blob/main/pipline.png)
The download link for the dataset is: https://pan.baidu.com/s/1LdZ0RvhxRgKY-_MV_yqluw?pwd=twy9 <br>
The extraction code is: twy9 <br>
Our code is coming soon


