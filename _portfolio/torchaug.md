---
title: "Torchaug"
collection: portfolio
permalink: /portfolio/torchaug
date: 2023-06-01
excerpt: '*PyTorch; Github Actions; CI/CD*<br/>[Github](https://github.com/juliendenize/torchaug)'
---

## About
Torchaug is a vision data augmentation library for the Pytorch ecosystem. It is inspired by Torchvision that significantly speeds up augmentations depending on the augmentation, device, and batch size, up to 4 times depending on the benchmarks.

It enriches Torchvision (v2) that has been implemented over Pytorch and Pillow to, among other things, perform data augmentations. Because it has been implemented first with per-sample CPU data augmentations in mind, it has several drawbacks to make it efficient:
- For data augmentations on GPU, some CPU/GPU synchronizations cannot be avoided.
- For data augmentations applied on batch, the randomness is sampled for the whole batch and not each sample.

Torchaug removes these issues and its transforms are meant to be used in place of Torchvision. It is based on the code base of Torchvision and therefore follows the same nomenclature as Torchvision with functional augmentations and transforms class wrappers. However, Torchaug does not support transforms on Pillow images.

To be sure to retrieve the same data augmentations as Torchvision, the components are tested to match Torchvision outputs.

## Code Link

[Github](https://github.com/juliendenize/torchaug)

## Stack

PyTorch; Github Actions; CI/CD
