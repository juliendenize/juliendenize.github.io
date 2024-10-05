---
title: "Individual Locating of Soccer Players from a Single Moving View"
collection: publications
permalink: /publication/calibration
excerpt: '[Paper link](https://www.mdpi.com/1424-8220/23/18/7938)'
date: 2023-09-16
venue: 'Sensors'
citation: '" Maglo, Adrien, Astrid Orcesi, Julien Denize, and Quoc Cuong Pham. 2023. "Individual Locating of Soccer Players from a Single Moving View" Sensors 23, no. 18: 7938. https://doi.org/10.3390/s23187938'
---

## Abstract
Positional data in team sports is key in evaluating the players’ individual and collective performances. When the sole source of data is a broadcast-like video of the game, an efficient video tracking method is required to generate this data. This article describes a framework that extracts individual soccer player positions on the field. It is based on two main components. As in broadcast-like videos of team sport games, the camera view moves to follow the action and a sport field registration method estimates the homography between the pitch and the frame space. Our method estimates the positions of key points sampled on the pitch thanks to an encoder–decoder architecture. The attention mechanisms of the encoder, based on a vision transformer, captures characteristic pitch features globally in the frames. A multiple person tracker generates tracklets in the frame space by associating, with bipartite matching, the player detections between the current and the previous frames thanks to Intersection-Over-Union and distance criteria. Tracklets are then iteratively merged with appearance criteria thanks to a re-identification model. This model is fine-tuned in a self-supervised way on the player thumbnails of the video sample to specifically recognize the fine identification details of each player. The player positions in the frames projected by the homographies allow the obtaining of the real position of the players on the pitch at every moment of the video. We experimentally evaluate our sport field registration method and our 2D player tracker on public datasets. We demonstrate that they both outperform previous works for most metrics. Our 2D player tracker was also awarded first place at the SoccerNet tracking challenge in 2022 and 2023.

## Resources

[Paper link](https://www.mdpi.com/1424-8220/23/18/7938)


## Citation
If you found our work useful, please consider citing us:

>```BibTex
>@Article{maglo_2023_calibration,
>   AUTHOR = {Maglo, Adrien and Orcesi, Astrid and Denize, Julien and Pham, Quoc Cuong},
>   TITLE = {Individual Locating of Soccer Players from a Single Moving View},
>   JOURNAL = {Sensors},
>   VOLUME = {23},
>   YEAR = {2023},
>   URL = {https://www.mdpi.com/1424-8220/23/18/7938},
>   DOI = {10.3390/s23187938}
>}
>```