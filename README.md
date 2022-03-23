# Encode-in-Style: Latent-based Video Encoding using StyleGAN2

> Trevine Oorloff, Yaser Yacoob  
> 
> We propose an end-to-end facial video encoding approach that facilitates data-efficient high-quality video re-synthesis by optimizing low-dimensional edits of a single Identity-latent. The approach builds on StyleGAN2 image inversion and multi-stage non-linear latent-space editing to generate videos that are nearly comparable to input videos. It economically captures face identity, head-pose, and complex facial motions at fine levels, and thereby bypasses training and person modeling which tend to hamper many re-synthesis approaches. The approach is designed with maximum data efficiency, where a single <i>W+</i> latent and 35 parameters per frame enable high-fidelity video rendering. This pipeline can also be used for puppeteering (i.e., motion transfer).

<a href="https://arxiv.org/"><img src="https://img.shields.io/badge/arXiv-b31b1b.svg" height=22.5></a>
<a href="https://trevineoorloff.github.io/Encode-in-Style.io/"><img src="https://img.shields.io/static/v1?label=webpage &message=Encode-in-Style&color=red" height=22.5></a>  

# Description   
Official repository of the "Encode-in-Style: Latent-based Video Encoding using StyleGAN2" paper. <br>
<i> Note: The code would be released in the future. </i>

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
