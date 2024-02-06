# VI-SLAM Point Clouds
This repository accompanies the paper "_3D Object Detection with VI-SLAM Point Clouds: The Impact of
Object and Environment Characteristics on Model Performance_", to appear in the Proceedings of IEEE ICRA 2024. It introduces **VIP500**, a dataset of 4772 VI-SLAM point clouds that covers 500 different object and environment configurations. We also provide **VIP500-D**, an accompanying dataset of 20 RGB-D point clouds of the object classes and shapes in VIP500, for comparison purposes.

# Datasets
The full VIP500 and VIP500-D datasets can be downloaded at the following Google Drive link:

Each point cloud in the VIP500 dataset is in .txt format, with each line specifying the coordinates of a point and the object class that point is associated with (x y z class). The numerical value in the class column refers to the following object class assignments (derived from the order in the ModelNet10 dataset):

0 - No object

3 - Chair

4 - Desk

8 - Sofa

9 - Table

Each point cloud in the VIP-500D dataset is in .pcd format.


