---
title: "COMEDIAN: Self-Supervised Learning and Knowledge Distillation for Action Spotting using Transformers"
collection: publications
permalink: /publication/comedian
excerpt: '[Paper link](https://arxiv.org/abs/2309.01270)'
date: 2023-09-23
venue: 'arXiv'
citation: '"COMEDIAN: Self-Supervised Learning and Knowledge Distillation for Action Spotting using Transformers" Julien Denize, Mykola Liashuha, Jaonary Rabarisoa, Astrid Orcesi, Romain Hérault; arXiv:abs/2309.01270, 2023'
---

## Abstract
We present COMEDIAN, a novel pipeline to initialize spatio-temporal transformers for action spotting, which involves self-supervised learning and knowledge distillation. Action spotting is a timestamp-level temporal action detection task. Our pipeline consists of three steps, with two initialization stages. First, we perform self-supervised initialization of a spatial transformer using short videos as input. Additionally, we initialize a temporal transformer that enhances the spatial transformer's outputs with global context through knowledge distillation from a pre-computed feature bank aligned with each short video segment. In the final step, we fine-tune the transformers to the action spotting task. The experiments, conducted on the SoccerNet-v2 dataset, demonstrate state-of-the-art performance and validate the effectiveness of COMEDIAN's pretraining paradigm. Our results highlight several advantages of our pretraining pipeline, including improved performance and faster convergence compared to non-pretrained models. 

## Resources

[Paper Link](https://arxiv.org/abs/2309.01270) - [Code Link](https://github.com/juliendenize/eztorch)


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@article{denize_2023_COMEDIAN,
>    author    = {Denize, Julien and Liashuha, Mykola and Rabarisoa, Jaonary and Orcesi, Astrid and H\'erault, Romain},
>    title     = {COMEDIAN: Self-Supervised Learning and Knowledge Distillation for Action Spotting using Transformers},
>    journal   = {arXiv},
>    volume    = {abs/2309.01270},
>    year      = {2023},
>    url       = {https://arxiv.org/abs/2309.01270},
>}
>```