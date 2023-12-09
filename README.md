# MIDNet
MIDNet: Deblurring Network for Material Microstructure Images

#### **Jiaxiang** Wang, Zhengyi Li, Peng Shi, Hongying Yu and Dongbai Sun*

> **Abstract:** Scanning electron microscopy (SEM) is a crucial tool in the field of materials science, providing valuable insights into the microstructural characteristics of materials. Unfortunately, SEM images often suffer from blurriness caused by improper hardware calibration or imaging automation errors, which present challenges in analyzing and interpreting material characteristics. Consequently, rectifying the blurring of these images assumes paramount significance to enable subsequent analysis. To address this issue, we introduce a Material Images Deblurring Network (MIDNet) built upon the foundation of the Nonlinear Activation Free Network (NAFNet). MIDNet is meticulously tailored to address the blurring in images capturing the microstructure of materials. The key contributions include enhancing the NAFNet architecture for better feature extraction and representation, integrating a novel soft attention mechanism to uncover important correlations between encoder and decoder, and introducing new multi-loss functions to improve training effectiveness and overall model performance. We conduct a comprehensive set of experiments utilizing the material blurry dataset and compare them to several state-of-the-art deblurring methods. The experimental results demonstrate the applicability and effectiveness of MIDNet in the domain of deblurring material microstructure images, with a PSNR (Peak Signal-to-noise Ratio) reaching 35.26dB and an SSIM (Structural Similarity) of 0.946. 



| <img src="./figures/5-1.gif" style="zoom:50%;" /> | <img src="./figures//one.gif" style="zoom:50%;" /> |
| :-----------------------------------------------: | :------------------------------------------------: |
|                      Deblur                       |                       Deblur                       |

### Dataset

We utilize a dataset containing 120 paired images with both low and high quality to investigate material microstructure fuzziness.

<<<<<<< HEAD
| ![img](README.assets/wps4.png) |  ![](README.assets/wps5.png)   |
| :----------------------------: | :----------------------------: |
| ![img](README.assets/wps6.png) | ![img](README.assets/wps7.png) |
| ![img](README.assets/wps8.png) | ![img](README.assets/wps9.png) |
|       Low-quality Images       |      High-quality Images       |



### Acknowledgement

We refer to code from [NAFNet](https://github.com/megvii-research/NAFNet). Their code helps me a lot. Thanks for their awesome works. 

NAFNet:   Chen L, Chu X, Zhang X, et al. Simple baselines for image restoration[C]//European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2022: 17-33.

=======
![exp_1](figures/5-1.gif)
>>>>>>> eb24da84b98c8b6cafb237229af8a14f515dae10
