## DHC: Dual-debiased Heterogeneous Co-training Framework for Class-imbalanced Semi-supervised Medical Image Segmentation (MICCAI 23)

Aiming to solve the Imbalanced class distribution issue, authors present a novel Dual-debiased Heterogeneous Cotraining (DHC) framework for semi-supervised 3D medical image segmentation. 为了解决类分布不均衡的问题，作者提出了一种用于半监督三维医学图像分割的新型双偏差异构训练（DHC）框架。

Specifically, we propose two loss weighting strategies, namely Distribution-aware Debiased Weighting (DistDW) and Difficulty-aware Debiased Weighting (DiffDW) 具体来说，我们提出了两种损失加权策略，即分布感知去偏权重（DistDW）和难度感知去偏权重（DiffDW）**which leverage the pseudo labels dynamically to guide the model to solve data and learning biases.**动态利用伪标签来指导模型，来解决数据和学习偏差。  

类不平衡问题在医学图像数据集中很常见。例如，CT扫描的多器官分割需要分割食管、右肾上腺、左肾上腺等，类别比例相当不平衡；见图1(a)。对于CT扫描肝脏肿瘤分割，通常肝脏与肿瘤的比例大于16:1。