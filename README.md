# A Semi-supervised Deep Learning-based Approach with Multiphase Active Contour Loss for Left Ventricle Segmentation from CMR Images 
## Introduction
This repository contains the implementation for automated endocardium (Endo) and epicardium (Epi) segmentation on the [ACDC-2017](https://www.creatis.insa-lyon.fr/Challenge/acdc/index.html) dataset introduced in the following paper: "A Semi-supervised Deep Learning-Based Approach with Multiphase Active Contour Loss for Left Ventricle Segmentation from CMR Images" [https://doi.org/10.1007/978-981-16-4538-9_2](https://doi.org/10.1007/978-981-16-4538-9_2).
## Our contributions
* Introducing a new loss functional that combines Mumford-Shah and Active Contour function
* Building the end-to-end model for multiphase segmentation based on U-Net architecture
![model](https://github.com/minhnhattrinh312/Multiphase-Active-Contour-Loss/blob/master/image/model.png)

## Citation
If you find this reference implementation useful in your research, please consider citing:
```
@inproceedings{trinh2022semi,
  title={A Semi-supervised Deep Learning-Based Approach with Multiphase Active Contour Loss for Left Ventricle Segmentation from CMR Images},
  author={Trinh, Minh-Nhat and Nguyen, Nhu-Toan and Tran, Thi-Thao and Pham, Van-Truong},
  booktitle={Proceedings of Third International Conference on Sustainable Computing},
  pages={13--23},
  year={2022},
  organization={Springer}
}
```
