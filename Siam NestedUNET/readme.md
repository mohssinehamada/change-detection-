Siam alleviates the loss of localization information in the deep layers of neural network through compact information transmission between encoder and decoder,
and between decoder and decoder. In addition, Ensemble Channel Attention Module (ECAM) is proposed for deep supervision. 
Through ECAM, the most representative features of different semantic levels can be refined and used for the final classification.

 "[SNUNet-CD: A Densely  Connected Siamese Network for Change Detection of VHR Images](https://ieeexplore.ieee.org/document/9355573) ". 
 
 "[Siamese NestedUNet Networks for Change Detection of High Resolution Satellite Image](https://dl.acm.org/doi/abs/10.1145/3437802.3437810)"
 ## Dataset

- [CDD](https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit) (Change Detection Dataset)
- paper: [Change detection in remote sensing images using conditional adversarial networks](https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLII-2/565/2018/isprs-archives-XLII-2-565-2018.pdf)

## Train from scratch

    python train.py

## Evaluate model performance

    python eval.py

## Visualization

    python visualization.py

## Pre-trained models

The pre-trained models in CDD dataset are available. 

[google drive](https://drive.google.com/drive/folders/1_aoUvMC8zWy4Pv7vU_BHu5yzzjgIsNXv?usp=sharing)

## Requirements

- Python 3.6

- Pytorch 1.4

- torchvision 0.5.0

```
# other packages needed
pip install opencv-python tqdm tensorboardX sklearn
```
