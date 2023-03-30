# SNUNet-CD

[SarasNET](img/model.jpg)

# SNUNet
[SNUNet](img/SNUNet.png)


# Planet-Labs-Disaster-Data-

### Summary

Implemented a pre-trained Siamese Network using Convolutional Neural Networks, Attention mechanism, Transformers and more, called "[SarasNET](https://github.com/f64051041/SARAS-Net)" to apply on satellite imagery data to develop a change detection model. The SarasNET is fine-tuned on different datasets such as CDD dataset to output relevant change masks. The NestedUNET folder contains code that works on the "[CDD dataset](https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit)" which the SarasNET is first fine-tuned on, enabling comparison of results and potential exploration of this direction.

Additionally, this repo contains code for a "[custom SiameseNET](https://arxiv.org/abs/1810.09111)"called CosimNET, originally used for scene detection and is trained from scratch to give an F1-score of 0.52 only with 100 epochs. This custom siamese network trained with only a single convolutional layer unlike in the paper is able to locate building changes adequately - demonstrating the discriminative capabilities and effectiveness of the approach.

Lastly, the last model is a simple Siamese Network which outputs a simalarity score given two bi-temporal images which is trained on a "[hurricane building damage dataset](https://ieee-dataport.org/open-access/detecting-damaged-buildings-post-hurricane-satellite-imagery-based-customized)" where there are no available ground truth masks and the labels at hand are only damaged and undamaged post hurricance.

These models can be helpful in monitoring damage from natural disasters given satellite imagery or be used to detect unauthorized structures (people living in trailers, camping etc) relating to land-use and land-cover change detection (Hawaii Land Trust, HILT).

All these three approaches can be a direction to work towards and research further on by the next cohort

## Dataset

- [CDD](https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit) (Change Detection Dataset)
- paper: [Change detection in remote sensing images using conditional adversarial networks](https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLII-2/565/2018/isprs-archives-XLII-2-565-2018.pdf)
- [IEEE](https://ieee-dataport.org/open-access/detecting-damaged-buildings-post-hurricane-satellite-imagery-based-customized) (Detecting Damaged Buildings Dataset)
