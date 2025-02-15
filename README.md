# Paper List | High Dynamic Range Imaging

A collection of HDR imaging papers. (Updating)

## Multi-Frame HDRI

| Title                                                        | Paper                                                        | Code                                                         | Dataset                | Key Words                                       |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :--------------------- | :---------------------------------------------- |
| Efficient HDR Reconstruction From Real-World Raw Images      | [arxiv-2023](https://arxiv.org/pdf/2306.10311.pdf)           |                                                              |                        |                                                 |
| RawHDR: High Dynamic Range Image Reconstruction from a Single Raw Image | [ICCV-2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Zou_RawHDR_High_Dynamic_Range_Image_Reconstruction_from_a_Single_Raw_ICCV_2023_paper.pdf)           |      [RawHDR](https://github.com/jackzou233/RawHDR)                                                        |                        |                                                 |
| A Unified HDR Imaging Method with Pixel and Patch Level      | [CVPR-2023](https://arxiv.org/pdf/2304.06943.pdf)            |                                                              |                        |                                                 |
| HDR Imaging with Spatially Varying Signal-to-Noise Ratios    | [CVPR-2023](https://arxiv.org/pdf/2303.17253.pdf)            |                                                              |                        |                                                 |
| SMAE: Few-shot Learning for HDR Deghosting with Saturation-Aware Masked Autoencoders | [CVPR-2023](https://arxiv.org/pdf/2304.06914.pdf)            |                                                              | Kalantari, Hu          | Few shot HDR                                    |
| Joint HDR Denoising and Fusion: A Real-World Mobile HDR Image Dataset | [CVPR-2023](https://web.comp.polyu.edu.hk/cslzhang/paper/CVPR23-Joint-HDRDN.pdf) | [Joint-HDRDN](https://github.com/shuaizhengliu/Joint-HDRDN)  | Mobile-HDR             | New mobile HDR dataset, Transformer-based model |
| Improving Dynamic HDR Imaging with Fusion Transformer        | [AAAI-2023](https://ojs.aaai.org/index.php/AAAI/article/view/25107) |                                                              |                        |                                                 |
| Robust Real-world Image Enhancement Based on Multi-Exposure LDR Images | [WACV-2023](https://openaccess.thecvf.com/content/WACV2023/html/Ren_Robust_Real-World_Image_Enhancement_Based_on_Multi-Exposure_LDR_Images_WACV_2023_paper.html) |                                                              | Kalantari&Various      | Cost volumn                                     |
| FlexHDR: Modelling Alignment and Exposure Uncertainties for Flexible HDR Imaging | [TIP-2022](https://arxiv.org/abs/2201.02625)                 |                                                              | Kalantari              | Arbitrary number of input LDRs, HDR flow        |
| **Selective TransHDR: Transformer-based selective HDR Imaging using Ghost Region Mask** | [ECCV-2022](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770292.pdf) |                                                              | Kalantari              | Ghost Region Mask                               |
| **Ghost-free High Dynamic Range Imaging with Context-aware Transformer** | [ECCV-2022](https://arxiv.org/pdf/2208.05114)                | [HDR-Transformer](https://github.com/megvii-research/HDR-Transformer) | Kalantari              | Context-Aware Transformer                       |
| A Lightweight Network for High Dynamic Range Imaging         | [CVPRW-2022](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Yan_A_Lightweight_Network_for_High_Dynamic_Range_Imaging_CVPRW_2022_paper.pdf) |                                                              | NTIRE                  | Two branch, Lightweight                         |
| Gamma-Enhanced Spatial Attention Network for Efficient High Dynamic Range Imaging | [CVPRW-2022](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Li_Gamma-Enhanced_Spatial_Attention_Network_for_Efficient_High_Dynamic_Range_Imaging_CVPRW_2022_paper.pdf) |                                                              | NTIRE                  | gamma-corrected                                 |
| Bidirectional Motion Estimation With Cyclic Cost Volume for High Dynamic Range Imaging | [CVPRW-2022](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Vien_Bidirectional_Motion_Estimation_With_Cyclic_Cost_Volume_for_High_Dynamic_CVPRW_2022_paper.pdf) |                                                              | NTIRE                  | Bidirectional Motion Estimation                 |
| Attention-Guided Progressive Neural Texture Fusion for High Dynamic Range Image Restoration | [TIP-2022](https://arxiv.org/pdf/2107.06211.pdf)             |                                                              | Kalnatari              | Two stream, Neural Feature Transfer             |
| Dual-Attention-Guided Network for Ghost-Free High Dynamic Range Imaging | [IJCV-2022](https://link.springer.com/article/10.1007/s11263-021-01535-y) |                                                              | Kalantari              |                                                 |
| High Dynamic Range Imaging of Dynamic Scenes with Saturation Compensation but without Explicit Motion Compensation | [WACV-2022](https://openaccess.thecvf.com/content/WACV2022/supplemental/Chung_High_Dynamic_Range_WACV_2022_supplemental.pdf) | [hdri-saturation-compensation](https://github.com/haesoochung/hdri-saturation-compensation) | Kalantari              | Brightness adjustment, Saturation mask          |
| Drbr-Hdr: Dual-Branch Recursive Band Reconstruction Network for Hdr with Large Motions | [SSRN-2022](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4147499) |                                                              | Kalantari              | Dual branch                                     |
| Learning Regularized Multi-Scale Feature Flow for High Dynamic Range Imaging | [arxiv-2022](https://arxiv.org/pdf/2207.02539.pdf)           |                                                              | Kalantari              | Multi-scale, Flow                               |
| High Dynamic Range Imaging via Gradient-aware Context Aggregation Network | [PR-2022](https://www.sciencedirect.com/science/article/pii/S0031320321005227) |                                                              | Kalantari              | Gradient information                            |
| Labeled from Unlabeled: Exploiting Unlabeled Data for Few-shot Deep HDR Deghosting | [CVPR-2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Prabhakar_Labeled_From_Unlabeled_Exploiting_Unlabeled_Data_for_Few-Shot_Deep_HDR_CVPR_2021_paper.pdf) | [FSHDR](https://github.com/Susmit-A/FSHDR)                   | Kalantari              | Few shot                                        |
| **HDR-GAN: HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions** | [TIP-2021](https://arxiv.org/abs/2007.01628)                 | [HDR-GAN](https://github.com/nonu116/HDR-GAN)                | Kalantari              | GAN                                             |
| Ghost-Free Deep High-Dynamic-Range Imaging Using Focus Pixels for Complex Motion Scenes | [TIP-2021](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9429936) |                                                              | own real-world dataset | Utilize focus pixel image                       |
| Self-Gated Memory Recurrent Network for Efficient Scalable HDR Deghosting | [TCI-2021](https://ieeexplore.ieee.org/document/9540317)     | [HDRRNN](https://github.com/Susmit-A/HDRRNN)                 | Kalantari + Prabhakar  | Recurrent                                       |
| ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging | [CVPRW-2021](https://arxiv.org/pdf/2105.10697.pdf)           | [ADNet](https://github.com/liuzhen03/ADNet)                  | NTIRE                  | PCD                                             |
| Progressive and Selective Fusion Network for High Dynamic Range Imaging | [MM-2021](https://arxiv.org/pdf/2108.08585.pdf)              |                                                              | Kalantari              | Progressive fusion                              |
| Merging-ISP: Multi-Exposure High Dynamic Range Image Signal Processing | [GCPR-2021](https://link.springer.com/chapter/10.1007/978-3-030-92659-5_21) |                                                              | Kalantari              | ISP                                             |
| Towards Accurate HDR Imaging with Learning Generator Constraints | [Neurocomputing-2021](https://www.sciencedirect.com/science/article/pii/S092523122031849X) |                                                              | Kalantari              | LDR-->HDR-->LDR                                 |
| Hierarchical Fusion for Practical Ghost-free High Dynamic Range Imaging | [MM-2021](https://dl.acm.org/doi/abs/10.1145/3474085.3475260) |                                                              | Kalantari              | Hierarchical fusion                             |
| **Deep HDR Imaging via A Non-Local Network**                 | [TIP-2020](https://ieeexplore.ieee.org/abstract/document/8989959) | [NHDRRNet (Keras-implementation)](https://github.com/tuvovan/NHDRRNet),  [NHDRRNet (PyTorch-re-implementation)](https://github.com/Galaxies99/NHDRRNet-pytorch) | Kalantari              | Non-local                                       |
| Towards Practical and Efficient High-resolution HDR Deghosting with CNN | [ECCV-2020](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660494.pdf) |                                                              | Kalantari              | Efficient                                       |
| Sensor-realistic Synthetic Data Engine for Multi-frame High Dynamic Range Photography | [CVPRW-2020](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Hu_Sensor-Realistic_Synthetic_Data_Engine_for_Multi-Frame_High_Dynamic_Range_Photography_CVPRW_2020_paper.pdf) | [code](https://github.com/nadir-zeeshan/sensor-realistic-synthetic-data) | synthetic data         | synthetic data from game engine                 |
| Ghost Removal via Channel Attention in Exposure Fusion       | [CVIU-2020](https://reader.elsevier.com/reader/sd/pii/S1077314220301132?token=988EBE214F2D779B43AFBD9865B305D565601632AE5B46780AB792995116FC17FE7FBFCE6C45ECE689F9F7BB11ACCA83&originRegion=us-east-1&originCreation=20221126071114) |                                                              | Kalantari              | Non-local                                       |
| Pyramid inter-attention for high dynamic range imaging       | [Sensors-2020](https://www.mdpi.com/1424-8220/20/18/5102)    |                                                              | Kalantari              | Attention                                       |
| Attention-Mask Dense Merger (Attendense) Deep HDR for Ghost Removal | [ICASSP-2020](http://www.personal.psu.edu/kmm1122/Publications/Attendense.pdf) |                                                              | Kalantari              | Attention Mask                                  |
| Exposure-Structure Blending Network for High Dynamic Range Imaging of Dynamic Scenes github\ | [Access-2020](https://ieeexplore.ieee.org/document/9125884)  | [ESBN](https://github.com/tkd1088/ESBN)                      | Kalantari              | Encoder-decoder                                 |
| Multi-scale Dense Networks for Deep High Dynamic Range Imaging | [WACV-2019](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8658831&tag=1) |                                                              | Kalantari              | Multi-scale, DenseUnet                          |
| **Attention-guided Network for Ghost-free High Dynamic Range Imaging** | [CVPR-2019](https://arxiv.org/abs/1904.10293)                | [AHDRNet](https://github.com/qingsenyangit/AHDRNet)          | Kalantari              | Channel Attention                               |
| Kernel Prediction Network for Detail-Preserving High Dynamic Range Imaging | [APSIPA-ASC-2019](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9023217) |                                                              | Kalantari              | Kernal prediction                               |
| Deep Multi-Stage Learning for HDR With Large Object Motions  | [ICIP-2019](https://ieeexplore.ieee.org/document/8803582)    |                                                              | Kalantari              | Generate virtual exposures                      |
| A Fast, Scalable, and Reliable Deghosting Method for Extreme Exposure Fusion | [ICCP-2019](https://ieeexplore.ieee.org/document/8747329)    | [Deep Deghosting HDR](https://github.com/rajat95/Deep-Deghosting-HDR) | Prabhakar              | Arbitrary number of inputs                      |
| **Deep High Dynamic Range Imaging with Large Foreground Motions** | [ECCV-2018](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Shangzhe_Wu_Deep_High_Dynamic_ECCV_2018_paper.pdf) | [DeepHDR](https://github.com/elliottwu/DeepHDR)              | Kalantari              | U-Net                                           |
| Deep HDR Reconstruction of Dynamic Scenes                    | [ICIVC 2018](https://ieeexplore.ieee.org/abstract/document/8492856) |                                                              | Kalantari+own          | FlowNet2.0                                      |
| **Deep high dynamic range imaging of dynamic scenes**        | [SIGGRAPH-2017](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/PaperData/SIGGRAPH17_HDR.pdf) | [Kalantari (Official MATLAB implementation)](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/PaperData/SIGGRAPH17_HDR_Code_v1.0.zip), [TensorFlow implementation](https://github.com/TH3CHARLie/deep-high-dynamic-range) | Kalantari              | Fisrt deep multi-frame HDRI                     |

## Single-Frame HDRI

| Title                                                        | Paper                                              | Code                                                         | Dataset | Key Words |
| :----------------------------------------------------------- | :------------------------------------------------- | :----------------------------------------------------------- | :------ | :-------- |
| A Two-stage Deep Network for High Dynamic Range Image Reconstruction | [CVPRW-2021](https://arxiv.org/pdf/2104.09386.pdf) | [code](https://github.com/sharif-apu/twostageHDR_NTIRE21)    | NTIRE   |           |
| Single Image HDR Reconstruction Using a CNN with Masked Features and Perceptual Loss | [SIGGRAPH 2020](https://arxiv.org/abs/2005.07335)  | [HDRCNN](https://github.com/marcelsan/Deep-HdrReconstruction) |         |           |



## HDRTV

| Title                                                        | Paper                                             | Code                                           | Dataset | Key Words |
| :----------------------------------------------------------- | :------------------------------------------------ | :--------------------------------------------- | :------ | :-------- |
| Learning a Practical SDR-to-HDRTV Up-conversion using New Dataset and Degradation Models | [CVPR-2023](https://arxiv.org/pdf/2303.13031.pdf) | [HDRTVDM](https://github.com/AndreGuo/HDRTVDM) |         |           |
|                                                              |                                                   |                                                |         |           |







## HDR Video

| Title                                                        | Paper                                                        | Code                                                        | Dataset                                                      | Key Words                          |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :---------------------------------------------------------- | :----------------------------------------------------------- | :--------------------------------- |
| HDR Video Reconstruction with a Large Dynamic Dataset in Raw and sRGB Domains | [arxiv-2023](https://arxiv.org/pdf/2304.04773.pdf)           | /                                                           |                                                              |                                    |
| HDR Video Reconstruction: A Coarse-to-fine Network and A Real-world Benchmark Dataset | [ICCV-2021](https://arxiv.org/abs/2103.14943)                | [DeepHDRVideo](https://github.com/guanyingc/DeepHDRVideo)   |                                                              | Coarse to fine, real world dataset |
| Deep HDR Video from Sequences with Alternating Exposures     | [Eurographics-2019](https://people.engr.tamu.edu/nimak/Data/Eurographics19_HDRVideo_LoRes.pdf) |                                                             |                                                              | First DL HDR Video                 |
| Creating cinematic wide gamut HDR-video for the evaluation of tone mapping operators and HDR-displays | [Digital photography-2014](https://imago.org/wp-content/uploads/2014/10/images_pdfs_EDUCATION_Cinematic_HDR_Video.pdf) | [Porject](https://www.hdm-stuttgart.de/vmlab/hdm-hdr-2014/) | [HDM-HDR-2014](https://www.hdm-stuttgart.de/vmlab/hdm-hdr-2014/) | HDR video data                     |

## Traditional Multi-frame HDR Imaging

| Title                                                        | Paper                                                        | Code                                            | Dataset | Key Words |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :---------------------------------------------- | :------ | :-------- |
| Single Image HDR Reconstruction Using a CNN with Masked Features and Perceptual Loss | [TPAMI 2015](https://joonyoung-cv.github.io/assets/paper/15_pami_robust_high.pdf) |                                                 |         |           |
| HDR Deghosting: How to deal with saturation?                 | [CVPR 2013](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.365.7215&rep=rep1&type=pdf) |                                                 |         |           |
| Robust patch-based HDR reconstruction of dynamic scenes      | [TOG 2012](https://people.engr.tamu.edu/nimak/Data/SIGASIA12_HDR_PatchBasedReconstruction_LoRes.pdf) | [Code](https://web.ece.ucsb.edu/~psen/hdrvideo) |         |           |

## HDR Challenges

| Title                                                        | Paper                                                        | Compeptition                                               | Dataset |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :--------------------------------------------------------- | :------ |
| NTIRE 2022 Challenge on High Dynamic Range Imaging : Methods and Results | [CVPRW-2022](https://arxiv.org/pdf/2205.12633.pdf#:~:text=This%20manuscript%20focuses%20on%20the,and%20different%20sources%20of%20noise) | [Competition](https://data.vision.ee.ethz.ch/cvl/ntire22/) | NTIRE   |
| NTIRE 2021 Challenge on High Dynamic Range Imaging: Dataset, Methods and Results | [CVPRW-2021](https://arxiv.org/abs/2106.01439)               | [Competition](https://data.vision.ee.ethz.ch/cvl/ntire21/) | NTIRE   |

## HDR Datasets

| Dataset                                                      | Amount                                            | Data type                 | GT   | Resolution     | Details                                                      |
| :----------------------------------------------------------- | :------------------------------------------------ | :------------------------ | :--- | :------------- | :----------------------------------------------------------- |
| [Mobile-HDR](https://github.com/shuaizhengliu/Joint-HDRDN)   | 115 dynamic+136 static                            | Real LDR + bracketing HDR | Yes  | 4K             | shot by mobile phones, daytime+nighttime                     |
| [NTIRE-HDR](https://competitions.codalab.org/competitions/28162) | 1500 (training) + 60 (validation) + 201 (testing) | Real HDR + synthetic LDR  | Yes  | 1900 x 1060    | 29 scenes                                                    |
| [Kalantari *et al.*](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/) | 74 (training) + 15 (testing)                      | Real LDR + bracketing HDR | Yes  | 1500 x 1000    | Multi-exposure, dynamic scenes                               |
| [Sen *et al.*](https://web.ece.ucsb.edu/~psen/hdrvideo)      | 8 (testing only)                                  | Real                      | No   | 1350 x 900     | Multi-exposure, dynamic scenes, collected from HDR videos [1] |
| [Tursen *et al.*](https://user.ceng.metu.edu.tr/~akyuz/files/eg2016/index.html) | 16 (testing only)                                 | Real                      | No   | 1024 x 682     | Multi-exposure, indoor and out door scenes                   |
| [Prabhakar *et al.*](https://val.cds.iisc.ac.in/HDR/ICCP19/) | 466 (training) + 116 (testing)                    | Real                      | Yes  | 1-4 Megapixels | Dynamic scenes of 3-7 images (Download permission denied)    |

**Reference**

[1][wang, l., & yoon, k. j. (2021). deep learning for hdr imaging: state-of-the-art and future trends. ieee transactions on pattern analysis and machine intelligence.](<https://arxiv.org/pdf/2110.10394.pdf>)

[2] Froehlich, J., Grandinetti, S., Eberhardt, B., Walter, S., Schilling, A., & Brendel, H. (2014, March). Creating cinematic wide gamut HDR-video for the evaluation of tone mapping operators and HDR-displays. In Digital photography X (Vol. 9023, pp. 279-288). SPIE.

## Interesting HDR Reading Materials

-   [High Dynamic Range Imaging (second edition)](https://last.hit.bme.hu/download/firtha/video/HDR/Erik%20Reinhard,%20Wolfgang%20Heidrich,%20Paul%20Debevec,%20Sumanta%20Pattanaik,%20Greg%20Ward,%20Karol%20Myszkowski%20High%20Dynamic%20Range%20Imaging,%20Second%20Edition%20Acquisition,%20Display,%20and%20Image-Based%20Lighting%20%202010.pdf)

## See other useful HDR paperlists

-   <https://github.com/vinthony/awesome-deep-hdr>
-   <https://github.com/ytZhang99/Awesome-HDR>
-   <https://github.com/lcybuzz/Low-Level-Vision-Paper-Record/blob/master/HDR.md>
