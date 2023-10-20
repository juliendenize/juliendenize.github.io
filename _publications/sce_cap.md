---
title: "Estimation Contrastive de la Similarité pour un Apprentissage Flou Auto-Supervisé"
collection: publications
permalink: /publication/sce_cap
excerpt: '[Conference link](https://caprfiap2022.sciencesconf.org/resource/page/id/30) - [Code Link](https://github.com/juliendenize/eztorch)'
date: 2022-04-13
venue: 'CAp'
citation: '"Estimation Contrastive de la Similarité pour un Apprentissage Flou Auto-Supervisé" Julien Denize, Jaonary Rabarisoa, Astrid Orcesi, Romain Hérault, Stéphane Canu; Conférence sur l’Apprentissage Automatique (CAp), 2022'
---

## Abstract
L'apprentissage par représentation contrastif est une méthode d'apprentissage auto-supervisée efficace. Plusieurs approches performantes se basent sur l'estimation contrastive du bruit (NCE) et considèrent les vues d'une instance comme positives et les autres instances comme du bruit auquel se discriminer. Cependant, les instances d'un jeu de données sont tirées de la même distribution et partagent des informations sémantiques. Une bonne représentation des données doit contenir les relations, ou similarité sémantique, entre les instances. L'apprentissage contrastif apprend implicitement les relations mais considérer les négatifs comme du bruit nuit à la qualité des relations apprises. Pour contourner ce problème, nous proposons une nouvelle formulation de l'apprentissage contrastif utilisant la similarité sémantique entre les instances, appelée Estimation Contrastive de la Similarité (SCE). Notre apprentissage peut être considéré comme un apprentissage contrastif flou. Au lieu de classer les positifs et les négatifs de manière stricte, nous proposons une distribution continue de classification basée sur la similarité sémantique. La distribution de similarité cible est calculée à partir d'instances faiblement augmentées. Elles sont jumelées à une vue augmentée forte qui contraste son positif tout en maintenant la distribution de similarité cible. Les résultats expérimentaux montrent que la méthode SCE surpasse ses bases de référence MoCov2 et ReSSL sur divers jeux de données et est compétitive avec l'état de l'art sur le protocole d'évaluation linéaire ImageNet.


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@article{Denize_2022_sce_CAp,
>  author       = {Denize, Julien and Rabarisoa, Jaonary and Orcesi, Astrid and H\'erault, Romain and Canu, St\'ephane},
>  title        = {Estimation Contrastive de la Similarité pour un Apprentissage Flou Auto-Supervisé},
>  journal      = {Conférence sur l’Apprentissage Automatique (CAp)},
>  year         = {2022},
>}
>```