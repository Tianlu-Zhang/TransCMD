# TransCMD
The official PyTorch implementation of our paper, coming soon.

### :bookmark:Brief Introduction
Contemporary multi-modal trackers achieve strong performance by leveraging complex backbones and fusion strategies, but this comes at the cost of computational efficiency, limiting their deployment in resource-constrained settings. On the other hand, compact multi-modal trackers are more efficient but often suffer from reduced performance due to limited feature representation.
To mitigate the performance gap between compact and more complex trackers, we introduce a cross-modality distillation framework. This framework includes a complementarity-aware mask autoencoder designed to enhance cross-modal interactions by selectively masking patches within a modality, thereby forcing the model to learn more robust multi-modal representations. Additionally, we present a specific-common feature distillation module that transfers both modality-specific and shared information from a more powerful model's backbone to the compact model. Moreover, we develop a multi-path selection distillation module to guide a simple fusion module in learning more accurate multi-modal information from a sophisticated fusion mechanism using multiple paths. 
Extensive experiments on six multi-modal tracking benchmarks demonstrate that the proposed tracker, despite being lightweight, outperforms most state-of-the-art methods, highlighting its effectiveness. Notably, our tiny variant achieves a PR score of 67.5\% on LasHeR, a PR score of 58.5\% on DepthTrack, and a PR score of 73.1\% on VisEvent with only 6.5 M parameters, while operating at 126 FPS on an NVIDIA 2080Ti GPU.

# Model Zoo

# Raw results
[Download here](https://drive.google.com/file/)

# To do
The code will be available after acceptance.

# Acknowledgment
This repo is based on ViPT and OSTrack, helps us to quickly implement our ideas.

- [OSTrack](https://github.com/botaoye/OSTrack) [[related paper](https://arxiv.org/abs/2203.11991)]
- [ViPT](https://github.com/ZikunZhou/SAOT)[[related paper](https://openaccess.thecvf.com/content/CVPR2023/html/Zhu_Visual_Prompt_Multi-Modal_Tracking_CVPR_2023_paper.html)]
