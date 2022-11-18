---
title: "Feasibility Analysis of POD and Deep-autoencoder for Indoor Environment CFD Prediction"
collection: publications
permalink: /publication/2022-11-01-AutoencodeCFD
excerpt: ''
date: 2022-11-01
venue: 'Working on'
paperurl: ''
citation: '<i></i>'
---

**Abstract**: 

**Aim and approach:**
This study aims to investigate the feasibility of employing two algorithms, proper orthogonal decomposition (POD) and deep-autoencoder for the fast and precise forecast of indoor airflow, meanwhile, the comparison of the performance between these two methods will be explored in the context of various typical simulation scenarios. The details of Computational fluid dynamic (CFD) model information and constructions of the two methods are shown herein. The present work is tested in a two-dimensional (2D) rectangular room with air velocity distribution as the target variable. The dataset was divided into training and test datasets at the ratio of 5:1 and adapt for POD and deep-autoencoder, respectively. Then, changes in the organization of deep-autoencoder with respect to the embedded domain knowledge is conducted to check the variation of simulation performance. 

**Scientific innovation and relevance:**
With the development of highly-insulated low energy and passive buildings, energy conservation and indoor environment in buildings attracts more attention than it has ever. CFD simulation plays a crucial role in indoor environments in the past decades. However, the significant computational effort still cannot be ignored. Therefore, improving the simulation efficiency without loss of accuracy is one of the key objectives of developing CFD simulation in indoor environment prediction, especially for the purposes of design phase assistance and optimizing control strategies of the energy system in the operational phase. In the dimensionality reduction field, some projection-based methods, such as POD, Dynamic mode decomposition (DMD) and Karhunen-Loeve expansion have been tested, but these approaches have limitations in solving non-linear problems. In this paper, Deep-autoencoder is employed to reduce the dimensionality of CFD simulations, as it’s non-linear nature of their formulation. The novelty lies in the efficient utilization of the implicit non-linear approaching abilities in deep autoencoder to address issues in the CFD simulation scenarios, as a promising surrogate model in a faster and more accurate manner.

**Preliminary results and conclusion:**
This study proposed a pipeline to adapting deep-autoencoder to predict the indoor environment. Preliminary results indicate that the trained deep-autoencoder outperforms the POD method in various CFD scenarios, especially for solving non-linear issues, in which the quantity and organizations of latent layers have a significant impact on its performance. In the comparison result, despite the advantageous prediction efficiency in POD due to …, deep-autoencoder presents promising indoor environment prediction with significantly less computational resources required than traditional CFD simulation. The neural network layers of deep-autoencoder have a significant effect on the simulation performance. With the network layers increasing, the model becomes more accurate, but the overfitting problem cannot be ignored. Adopting suitable network layers is a key point of this study.


[Download paper here]()

**Citation**:<i></i>
