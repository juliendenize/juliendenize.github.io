---
title: "Similarity Contrastive Estimation for Image and Video Soft Contrastive Self-Supervised Learning"
collection: publications
permalink: /publication/sce_extended
excerpt: '[Paper link](https://link.springer.com/article/10.1007/s00138-023-01444-9) - [Code Link](https://github.com/juliendenize/eztorch)'
date: 2023-09-26
venue: 'MVAP'
citation: '"Similarity Contrastive Estimation for Image and Video Soft Contrastive Self-Supervised Learning" Julien Denize, Jaonary Rabarisoa, Astrid Orcesi, Romain Hérault; Machine Vision and Applications, 2023'
---

## Abstract
Contrastive representation learning has proven to be an effective self-supervised learning method for images and videos. Most successful approaches are based on Noise Contrastive Estimation (NCE) and use different views of an instance as positives that should be contrasted with other instances, called negatives, that are considered as noise. However, several instances in a dataset are drawn from the same distribution and share underlying semantic information. A good data representation should contain relations between the instances, or semantic similarity and dissimilarity, that contrastive learning harms by considering all negatives as noise. To circumvent this issue, we propose a novel formulation of contrastive learning using semantic similarity between instances called Similarity Contrastive Estimation (SCE). Our training objective is a soft contrastive one that brings the positives closer and estimates a continuous distribution to push or pull negative instances based on their learned similarities. We validate empirically our approach on both image and video representation learning. We show that SCE performs competitively with the state of the art on the ImageNet linear evaluation protocol for fewer pretraining epochs and that it generalizes to several downstream image tasks. We also show that SCE reaches state-of-the-art results for pretraining video representation and that the learned representation can generalize to video downstream tasks.

## Resources

[Paper Link](https://link.springer.com/article/10.1007/s00138-023-01444-9) - [Code Link](https://github.com/juliendenize/eztorch)


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@article{Denize_2023_sce_MVAP,
>   author={Denize, Julien and Rabarisoa, Jaonary and Orcesi, Astrid and H{\'e}rault, Romain},
>   title={Similarity contrastive estimation for image and video soft contrastive self-supervised learning},
>   journal={Machine Vision and Applications},
>   year={2023},
>   volume={34},
>   number={6},
>   doi={10.1007/s00138-023-01444-9},
>}
>```