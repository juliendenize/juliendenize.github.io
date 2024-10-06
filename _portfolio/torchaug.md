---
title: "Torchaug"
collection: portfolio
permalink: /portfolio/torchaug
excerpt: 'Pytorch; Github Actions; CI/CD'
date: 2023-06-01
citation: '[Github](https://github.com/juliendenize/torchaug)'
---

## About
Torchaug is a data augmentation library for the Pytorch ecosystem. It is meant to deal efficiently with tensors that are either on CPU or GPU and either per sample or on batches.

It enriches Torchvision (v2) that has been implemented over Pytorch and Pillow to, among other things, perform data augmentations. Because it has been implemented first with per-sample CPU data augmentations in mind, it has several drawbacks to make it efficient:
- For data augmentations on GPU, some CPU/GPU synchronizations cannot be avoided.
- For data augmentations applied on batch, the randomness is sampled for the whole batch and not each sample.

Torchaug removes these issues and its transforms are meant to be used in place of Torchvision. It is based on the code base of Torchvision and therefore follows the same nomenclature as Torchvision with functional augmentations and transforms class wrappers. However, Torchaug does not support transforms on Pillow images.

More details can be found in the documentation.

To be sure to retrieve the same data augmentations as Torchvision, the components are tested to match Torchvision outputs.

## Code Link

[Github](https://github.com/juliendenize/torchaug)
