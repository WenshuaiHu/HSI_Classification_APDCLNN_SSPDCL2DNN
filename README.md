# Pseudo Complex-Valued Deformable ConvLSTM Neural Network With Mutual Attention Learning for Hyperspectral Image Classification

Related code will be released gradually.

# Abstract:

Convolutional long short-term memory (ConvLSTM) has received much attention for hyperspectral image (HSI) classification due to its ability of modeling long-range correlations, which, however, is vulnerable to too many parameters and insufficient training, limiting its classification accuracy, especially for small samples. Different from it, traditional hand-crafted methods extract the features with basic attributes of HSIs, which can provide the lack of details and interpretability of deep semantic features. However, existing methods fail to incorporate their complementarity for HSI classification. As such, a Pseudo complex-valued (CV) Deformable ConvLSTM Neural Network with mutual Attention learning (APDCLNN) is proposed, providing a new way to realize the collaborative learning of hand-crafted and deep features for HSI classification. First, a 2-D pseudo CV deformable ConvLSTM (PDConvLSTM2D) cell is designed using deformable convolution and complex operations, with which a spatial–spectral PDConvLSTM2D neural network (SSPDCL2DNN) is built to extract scale- and spectral-enhanced deep spatial–spectral features. Then, 3-D Gabor filter is used to extract hand-crafted features, and a mutual attention-based multimodality feature learning and fusion (MAMLF) module is designed to integrate them into deep features for training and optimization of SSPDCL2DNN. Finally, an attention loss subnetwork is designed to refine the classification results. As we know, this is the first attempt to apply the idea of mutual attention learning to fuse hand-crafted and deep features for HSI classification. Extensive experiments on three widely used HSI datasets show the advantages of our model over other deep methods in terms of both quantitative and visual quality.


# Paper
Please cite our paper if you find the code or dataset useful for your research.

@ARTICLE{9816024,
  author={Hu, Wen-Shuai and Li, Heng-Chao and Wang, Rui and Gao, Feng and Du, Qian and Plaza, Antonio},<br>
  journal={IEEE Transactions on Geoscience and Remote Sensing}, <br>
  title={Pseudo Complex-Valued Deformable ConvLSTM Neural Network With Mutual Attention Learning for Hyperspectral Image Classification}, <br>
  year={2022},<br>
  volume={60},<br>
  number={},<br>
  pages={1-17},<br>
  keywords={Feature extraction;Neural networks;Convolution;Training;Representation learning;Logic gates;Data models;Complex-valued (CV) representation;convolutional long short-term memory (ConvLSTM);feature fusion;hyperspectral image (HSI) classification;mutual attention learning},<br>
  doi={10.1109/TGRS.2022.3188791}}

  # Requirements
  CUDA Version: 8.0

  Tflearn Version: 0.3.2
  
  Tensorflow-GPU Version: 1.4.0
  
  Python Version: 3.5.4

# Note
