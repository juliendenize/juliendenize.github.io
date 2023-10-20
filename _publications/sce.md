---
title: "Similarity Contrastive Estimation for Self-Supervised Soft Contrastive Learning"
collection: publications
permalink: /publication/sce
excerpt: '[Paper link](https://openaccess.thecvf.com/content/WACV2023/papers/Denize_Similarity_Contrastive_Estimation_for_Self-Supervised_Soft_Contrastive_Learning_WACV_2023_paper.pdf) - [Code Link](https://github.com/juliendenize/eztorch)'
date: 2023-01-03
venue: 'WACV'
citation: '"Similarity Contrastive Estimation for Self-Supervised Soft Contrastive Learning" Julien Denize, Jaonary Rabarisoa, Astrid Orcesi, Romain Hérault, Stéphane Canu; Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2023, pp. 2706-2716'
---

## Abstract
Contrastive representation learning has proven to be an effective self-supervised learning method. Most successful approaches are based on Noise Contrastive Estimation (NCE) and use different views of an instance as positives that should be contrasted with other instances, called negatives, that are considered as noise. However, several instances in a dataset are drawn from the same distribution and share underlying semantic information. A good data representation should contain relations, or semantic similarity, between the instances. Contrastive learning implicitly learns relations but considering all negatives as noise harms the quality of the learned relations. To circumvent this issue, we propose a novel formulation of contrastive learning using semantic similarity between instances called Similarity Contrastive Estimation (SCE). Our training objective is a soft contrastive learning one. Instead of hard classifying positives and negatives, we estimate from one view of a batch a continuous distribution to push or pull instances based on their semantic similarities. This target similarity distribution is sharpened to eliminate noisy relations. The model predicts for each instance, from another view, the target distribution while contrasting its positive with negatives. Experimental results show that SCE is Top-1 on the ImageNet linear evaluation protocol at 100 pretraining epochs with 72.1% accuracy and is competitive with state-of-the-art algorithms by reaching 75.4% for 200 epochs with multi-crop. We also show that SCE is able to generalize to several tasks

## Resources

[Paper Link](https://arxiv.org/abs/2111.14585) - [Code Link](https://github.com/juliendenize/eztorch)


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@InProceedings{Denize_2023_sce_WACV,
>    author    = {Denize, Julien and Rabarisoa, Jaonary and Orcesi, Astrid and H\'erault, Romain and Canu, St\'ephane},
>    title     = {Similarity Contrastive Estimation for Self-Supervised Soft Contrastive Learning},
>    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
>    month     = {January},
>    year      = {2023},
>    pages     = {2706-2716}
>}
>```