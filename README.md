# Expressive Talking Head Video Encoding in StyleGAN2 Latent-Space

> Trevine Oorloff, Yaser Yacoob  
> 
> While the recent advances in research on video re-enactment have yielded promising results, the approaches fall short in capturing the fine, detailed, and expressive facial features (e.g., lip-pressing, mouth puckering, mouth gaping, and wrinkles) which are crucial in generating realistic animated face videos. To this end, we propose an end-to-end expressive face video encoding approach that facilitates data-efficient high-quality video re-synthesis by optimizing low-dimensional edits of a single Identity-latent. The approach builds on StyleGAN2 image inversion and multi-stage non-linear latent-space editing to generate videos that are nearly comparable to input videos. While existing StyleGAN latent-based editing techniques focus on simply generating plausible edits of static images, we automate the latent-space editing to capture the fine expressive facial deformations in a sequence of frames using an encoding that resides in the Style-latent-space (StyleSpace) of StyleGAN2. The encoding thus obtained could be super-imposed on a single Identity-latent to facilitate re-enactment of face videos at 1024<sup>2</sup>. The proposed framework economically captures face identity, head-pose, and complex expressive facial motions at fine levels, and thereby bypasses training, person modeling, dependence on landmarks/ keypoints, and low-resolution synthesis which tend to hamper most re-enactment approaches. The approach is designed with maximum data efficiency, where a single <it>W+</it> latent and 35 parameters per frame enable high-fidelity video rendering. This pipeline can also be used for puppeteering (i.e., motion transfer).

<a href="https://arxiv.org/abs/2203.14512"><img src="https://img.shields.io/badge/arXiv-2203.14512-b31b1b.svg" height=22.5></a>
<a href="https://trevineoorloff.github.io/ExpressiveFaceVideoEncoding.io/"><img src="https://img.shields.io/static/v1?label=webpage &message=ExpressiveFaceVideoEncoding&color=darkgreen" height=22.5></a>  

# Description   
Official repository of the "Expressive Talking Head Video Encoding in StyleGAN2 Latent-Space" paper. <br>
<i> Note: The code and dataset used would be released in the future. </i>

# Table of Contents
- [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
- [Dataset](#dataset)
- [Data Pre-processing](#data-preprocessing)
- [Head-Pose Encoding](#head-pose-encoding)
- [Facial Attribute Encoding](#facial-attribute-ecoding)
- [Rendering](#rendering)
- [Generator Fine-tuning](#generator-fine-tuning)
- [Evaluation](#evaluation)
- [Acknowledgments](#acknowledgments)
- [Bibtex](#bibtex)
