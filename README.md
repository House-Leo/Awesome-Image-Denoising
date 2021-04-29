# Quick navigation

- [Datasets](datasets.md)
- [Papers](#paper)
  - [Non-DL based approach](non_dl_papers.md)
  - [DL based approach](#DL-based-approach)
    - [2014-2016](2014-2016_papers.md)
    - [2017](2017_papers.md)
    - [2018](2018_papers.md)
    - [2019](2019_papers.md)
    - [2020](2020_papers.md)
    - [2021](#2021)
- [Image Denoising Workshop papers](workshops.md)
- [Image Denoising Survey (DL-based)](survey.md)
- [Metric](#Metric)

# Awesome-Image-Denoising

Collect image denoising related papers, datasets, especially **real-world image denoising**. 

I am still collecting the relevant paper, ***if you want to add your own paper on this repository, feel free to open issue or contact me*** by sending mail to  `lihao9605 [at] gmail.com`, I will update your paper ASAP.

**If you like this repo, Star or Fork to support my work. Thank you.**

## Papers

### DL based approach

**Noted this collection is based on the summary of  [z-bingo's work](https://github.com/z-bingo/awesome-image-denoising-state-of-the-art).**

### 2021

More years papers, please check Quick navigation.

| Model             | Published                                    | Code                                                         | Title                                                        |
| ----------------- | -------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ |
| MPRNet            | [CVPR2021](https://arxiv.org/abs/2101.02808) | [Code]()                                                     | Multi-Stage Progressive Image Restoration                    |
| Neighbor2Neighbor | [CVPR2021](https://arxiv.org/abs/2101.02824) | [Code](https://github.com/TaoHuang2018/Neighbor2Neighbor)    | Neighbor2Neighbor: Self-Supervised Denoising from Single Noisy Images |
| NBNet             | [CVPR2021](https://arxiv.org/abs/2012.15028) | [Code](https://github.com/megvii-research/NBNet)             | NBNet: Noise Basis Learning for Image Denoising with Subspace Projection |
| PIPT              | [CVPR2021](https://arxiv.org/abs/2012.00364) | [Code](https://github.com/Ascend/mindspore/tree/19147e9cb97746e69f64dd486778ecd4e8b0fd8e/model_zoo/research/cv/IPT) | Pre-Trained Image Processing Transformer                     |
| Pseudo-ISP        | [arxiv](https://arxiv.org/abs/2103.10234)    | [Code](https://github.com/happycaoyue/Pseudo-ISP)            | Pseudo-ISP: Learning Pseudo In-camera Signal Processing Pipeline from A Color Image Denoiser |
| VDID              | [arxiv](https://arxiv.org/abs/2104.00965)    | [Code](https://github.com/JWSoh/VDIR)                        | Variational Deep Image Denoising                             |

------

## Metric

#### Commonly Used Image Quality Metric Code

 * PSNR (Peak Signal-to-Noise Ratio) [[Wiki]](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) [[Matlab Code]](https://www.mathworks.com/help/images/ref/psnr.html) [[Python Code]](https://github.com/aizvorski/video-quality) [[PyTorch Code]](https://github.com/z-bingo/FastDVDNet/blob/master/utils/data_utils.py#L13)

 * SSIM (Structural similarity) [[Wiki]](https://en.wikipedia.org/wiki/Structural_similarity) [[Matlab Code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py) [[PyTorch Code]](https://github.com/z-bingo/FastDVDNet/blob/master/utils/data_utils.py#L26)

 * NIQE (Naturalness Image Quality Evaluator) [[Web]](http://live.ece.utexas.edu/research/Quality/nrqa.htm) [[Matlab Code]](http://live.ece.utexas.edu/research/Quality/nrqa.htm)[[Python Code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)

------

***This repository is referenced from [Awesome-Super-Resolution](https://github.com/ChaofWang/Awesome-Super-Resolution)***. Thanks for [ChaofWang's work](https://github.com/ChaofWang).