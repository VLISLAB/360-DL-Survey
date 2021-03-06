## Geometric Structure Based and Regularized Depth Estimation From 360-degree Indoor Imagery

- year: 2020

- dataset: Shanghaitech-Kujiale Indoor 360-degree dataset (3550 indoor 360-degree dataset, self-collected) and Stanford2D3D dataset

- Abstract: Motivated by the correlation between the depth and the geometric structure of a 360-degree indoor image, we propose a novel learning-based depth estimation framework that leverages the geometric structure of a scene to conduct depth estimation. Also, to validate the effectiveness of each component in our framework under controlled conditions, we render a synthetic dataset.
- Contributions:
(1) We propose the representation of an indoor panorama as a collection of geometric structures with points, lines and planes. Such representation is beneficial for depth estimation, 3D reconstruction and counterfactual depth; (2) We propose leveraging geometric structure as both a prior and a regularizer in a novel framework for depth estimation; (3) We build a synthetic dataset for performance evaluation.

- Structure: Depth estimation module, Structure as a prior module, and Structure as a regularizer module

<img src="https://github.com/VLISLAB/360-DL-Survey/blob/main/Images/Geometric-aware.png" width="70%" height="70%">

- Results：
<img src="https://github.com/VLISLAB/360-DL-Survey/blob/main/Images/Geometric-aware_exp1.png" width="50%" height="50%">

-Analysis: This work novely introduces geometric structure (corner, line and plane) as a prior and a regularizer to facilitate 360-degree depth estimation. In addition, as furniture in indoor scenes cause difficulties to geometric structures, they also propose a synthetic dataset. However, they need more information for training, and the appropriate scenes are also limited for the visualization of geometric structures.



