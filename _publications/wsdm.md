---
title: "Incomplete Graph Learning via Attribute-Structure Decoupled Variational Auto-Encoder"
collection: publications
permalink: files/KDD2022_Landslide.pdf
date: 2023-10-20

venue: 'WSDM 2024. First Author'
---
'Graph Neural Networks (GNNs) conventionally operate under the assumption that node attributes are entirely observable. Their performance notably deteriorates when confronted with incomplete graphs due to the inherent message-passing mechanisms. While current solutions either employ classic imputation techniques or adapt GNNs to tolerate missed attributes. However, their ability to generalize is impeded especially when dealing with high rates of missing attributes.
To address this, we harness the representations of the essential views on graph—attributes and structures—into a common shared latent space, ensuring robust tolerance even at high missing rates. Our proposed neural model, named ASD-VAE, parameterizes such space via a coupled-and-decoupled learning procedure, reminiscent of brain cognitive processes and multimodal fusion.
Initially, ASD-VAE separately encodes attributes and structures, generating representations for each view. A shared latent space is then learned by maximizing the likelihood of the joint distribution of different view representations through coupling. Then, the shared latent space is decoupled into separate views, and the reconstruction loss of each view is calculated. Finally, the missing values of attributes are imputed from this learned latent space. 
In this way, the model offers enhanced resilience against skewed and biased distributions typified by missing information and subsequently brings benefits to downstream graph machine-learning tasks. Extensive experiments conducted on four typical real-world incomplete graph datasets demonstrate the superior performance of ASD-VAE against the state-of-the-art.'
