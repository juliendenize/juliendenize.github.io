---
title: "DIOD: Self-Distillation Meets Object Discovery"
collection: publications
permalink: /publication/diod
excerpt: '[Paper link](https://openaccess.thecvf.com/content/CVPR2024/papers/Kara_DIOD_Self-Distillation_Meets_Object_Discovery_CVPR_2024_paper.pdf) - [Code Link](https://github.com/CEA-LIST/DIOD)'
date: 2024-06-17
venue: 'CVPR'
citation: '"Sandra Kara, Hejer Ammar, Julien Denize, Florian Chabot, Quoc-Cuong Pham; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 3975-3985 '
---

## Abstract
Instance segmentation demands substantial labeling resources. This has prompted increased interest to explore the object discovery task as an unsupervised alternative. In particular promising results were achieved in localizing instances using motion supervision only. However the motion signal introduces complexities due to its inherent noise and sparsity which constrains the effectiveness of current methodologies. In the present paper we propose DIOD (self DIstillation meets Object Discovery) the first method that places the motion-guided object discovery within a framework of continuous improvement through knowledge distillation providing solutions to existing limitations (i) DIOD robustly eliminates the noise present in the exploited motion maps providing accurate motion-supervision (ii) DIOD leverages the discovered objects within an iterative pseudo-labeling framework enriching the initial motion-supervision with static objects which results in a cost-efficient increase in performance. Through experiments on synthetic and real-world datasets we demonstrate the benefits of bridging the gap between object discovery and distillation by significantly improving the state-of-the-art. This enhancement is also sustained across other demanding metrics so far reserved for supervised tasks.

## Resources

[Paper Link](https://openaccess.thecvf.com/content/CVPR2024/papers/Kara_DIOD_Self-Distillation_Meets_Object_Discovery_CVPR_2024_paper.pdf) - [Code Link](https://github.com/CEA-LIST/DIOD)


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@InProceedings{Kara_2024_CVPR,
>    author    = {Kara, Sandra and Ammar, Hejer and Denize, Julien and Chabot, Florian and Pham, Quoc-Cuong},
>    title     = {DIOD: Self-Distillation Meets Object Discovery},
>    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
>    month     = {June},
>    year      = {2024},
>    pages     = {3975-3985}
>}
>```