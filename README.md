# awesome-SegmentAnything-Medical-Images

In this repo I try to collect a list of papers and projects that I find interesting that utilizes the *Segment Anything Model (SAM)* to perform segmentation on medical images, utilizes SAM as part of the frameworks, or perform anaylsis or studies of SAM on medical images. Note that this SAM is a relative new model and there may be ignored papers or works that are ignored. 

For a list of all projects and researches of SAM in various fields, check out the [Awesome Segment Anything](https://github.com/Hedlen/awesome-segment-anything) repository.

If you find any interesting works feel free to create pull requests or [*email* me](mailto:knight16729438@gmail.com) to make the list more comprehensive.



### Survey 



| Title                  | Paper                  | Code                                                    | Dataset                                                         | Keywords | Comments                                                     |
| ---------------------- | ---------------------- |  ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|SAM.MD: Zero-shot medical image segmentation capabilities of the Segment Anything Mode |  [arxiv](https://arxiv.org/pdf/2304.05396.pdf) | - | abdominal CT organ | zero-shot | comparasion between prompted SAM and 2D and 3D nnUNet |
| Segment Anything Model (SAM) for Digital Pathology: Assess Zero-shot Segmentation on Whole Slide Imaging |  [arxiv](https://arxiv.org/pdf/2304.04155.pdf) | - | Skin tumor, Skin tissue | zero-shot | comparasion between prompted SAM and SimTriplet 



### Related Projects

| Title                  | Demo                  | Paper |Code                                                    |                      Comments                                                     |
| ---------------------- | ---------------------- |  ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|SAMM (Segment Any Medical Model): A 3D Slicer Integration to SAM | | [arxiv](https://arxiv.org/pdf/2304.05622.pdf) | [code](https://github.com/bingogome/samm)  | SAM integration in 3D Slicer for semi-automatic segmentation
|Segment Anything Model (SAM) in Napari | | - | [code](https://github.com/MIC-DKFZ/napari-sam) | SAM integration in 3D Napari for click-based semantic segmentation
|SAM Medical Imaging | | - | [code](https://github.com/amine0110/SAM-Medical-Imaging) | SAM segmentaiton of DICOM files using [Colab](https://colab.research.google.com/drive/1slN4dnIHGrc_eiUXaa27lRUFNZ9TIwOX?usp=sharing)
|Segment-Anything-Automatically-on-Medical-Image (SAAMI) | | - | [code](https://github.com/AxDante/SAAMI) | Automatic SAM 3D segmentation mask generation without prompting


<!-- |DIVA: Deep Unfolded Network from Quantum Interactive Patches for Image Restoration | DIVA | [arxiv](https://arxiv.org/pdf/2301.00247.pdf) | - |- |
|DLGSANet: Lightweight Dynamic Local and Global Self-Attention Networks for Image Super-Resolution | DLGSANet | [arxiv](https://arxiv.org/pdf/2301.02031.pdf) | [code](https://neonleexiang.github.io/DLGSANet) |- |
|The Best of Both Worlds: A Framework for Combining Degradation Prediction with High Performance Super-Resolution Networks | - | [MDPI Sensors](https://doi.org/10.3390/s23010419) | [code](https://github.com/um-dsrg/RUMpy) |- |
|Image Super-Resolution using Efficient Striped Window Transformer | ESWT | [arxiv](https://arxiv.org/pdf/2301.09869.pdf) | [code](https://github.com/Fried-Rice-Lab/FriedRiceLab) |SISR|
|A statistically constrained internal method for single image super-resolution | - | [arxiv](https://arxiv.org/pdf/2302.01648.pdf) |  |-|
|OSRT: Omnidirectional Image Super-Resolution with Distortion-aware Transformer | OSRT | [arxiv](https://arxiv.org/pdf/2302.03453.pdf) | - |ODISR|
|Denoising Diffusion Probabilistic Models for Robust Image Super-Resolution in the Wild | SR3+ | [arxiv](https://arxiv.org/pdf/2302.07864.pdf) | - |blind SR, DDPMs|
|Kernelized Back-Projection Networks for Blind Super Resolution | KCBPN/KBPN | [arxiv](https://arxiv.org/pdf/2302.08478.pdf) | [code](https://github.com/Yuki-11/KBPN) |blind SR|
|Improving Scene Text Image Super-Resolution via Dual Prior Modulation Network | DPMN | [arxiv](https://arxiv.org/pdf/2302.10414.pdf) | [code](https://github.com/jdfxzzy/DPMN) |Scene text SR|
|CDPMSR: CONDITIONAL DIFFUSION PROBABILISTIC MODELS FOR SINGLE IMAGE SUPER-RESOLUTION | CDPMSR | [arxiv](https://arxiv.org/pdf/2302.12831.pdf) | - |DDPMs|
|Spatially-Adaptive Feature Modulation for Efficient Image Super-Resolution | SAFMN | [arxiv](https://arxiv.org/pdf/2302.13800.pdf) | [code](https://github.com/sunny2109/SAFMN) |SISR, lightweight|
|Efficient and Explicit Modelling of Image Hierarchies for Image Restoration | GRL | [CVPR23](https://arxiv.org/pdf/2303.00748.pdf) | [code](https://github.com/ofsoundof/GRL-Image-Restoration) |SISR|
|Zero Shot Image Restoration Using Denoising Diffusion Null-Space Model  | DDNM | [ICLR23](https://arxiv.org/pdf/2212.00490.pdf) | [code](https://github.com/wyhuai/DDNM/tree/main) |DDNM|
|Unlimited-Size Diffusion Restoration | - | [arxiv](https://arxiv.org/pdf/2303.00354.pdf) | [code](https://github.com/wyhuai/DDNM/tree/main) |DDNM|
|OPE-SR: Orthogonal Position Encoding for Designing a Parameter-free Upsampling Module in Arbitrary-scale Image Super-Resolution | OPE | [CVPR23](https://arxiv.org/pdf/2303.01091.pdf) | - |Arbitrary-scale SR|
|Super-Resolution Neural Operator | SRNO | [CVPR23](https://arxiv.org/pdf/2303.02584.pdf) | [code](https://github.com/2y7c3/Super-Resolution-Neural-Operator) |continuous SR|
|Self-Asymmetric Invertible Network for Compression-Aware Image Rescaling | SAIN | [AAAI23](https://arxiv.org/pdf/2303.02353.pdf) | - |Image Rescaling|
|QuickSRNet: Plain Single-Image Super-Resolution Architecture for Faster Inference on Mobile Platforms | QSRNet | [arxiv](https://arxiv.org/pdf/2303.04336.pdf) | - |SISR, lightweight|
|Burstormer: Burst Image Restoration and Enhancement Transformer | Burstormer | [CVPR23](https://arxiv.org/pdf/2304.01194.pdf) | [code](https://github.com/akshaydudhane16/Burstormer) ||
|Better “CMOS” Produces Clearer Images:Learning Space-Variant Blur Estimation for Blind Image Super-Resolution | CMOS | [CVPR23](https://arxiv.org/pdf/2304.03542.pdf) | [code](https://github.com/ByChelsea/CMOS) |Blind SR|
|Waving Goodbye to Low-Res: A Diffusion-Wavelet Approach for Image Super-Resolution | DiWa | [arxiv](https://arxiv.org/abs/2304.01994) | - |Diffusion-Wavelet|
|Generative Diffusion Prior for Unified Image Restoration and Enhancement | GDP | [CVPR23](https://arxiv.org/pdf/2304.01247.pdf) | [code](https://generativediffusionprior.github.io) |unified image recovery| -->