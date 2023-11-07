1. Set up the environment by following the steps here: https://mmpose.readthedocs.io/en/latest/installation.html
2. Download dataset by running data.sh (It takes while, and takes 10~20 GB so be careful!)
3. Download annotation file 





Demo(?)

Since there's no explicit 3d whole body model I just put some 

Demo contains 3 sub models

1. Detection 
demo/mmdetection_cfg/rtmdet_m_640-8xb32_coco-person.py \



2. Img -> 2d Whole
configs/body_2d_keypoint/rtmpose/body8/rtmpose-m_8xb256-420e_body8-256x192.py \

3. Img, 2d -> 3d whole(???)
configs/body_3d_keypoint/video_pose_lift/h36m/video-pose-lift_tcn-243frm-supv-cpn-ft_8xb128-200e_h36m.py \
