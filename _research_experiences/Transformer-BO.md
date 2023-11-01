---
title: "Transformer-based Bayesian Optimization"
collection: publications
index: 1
excerpt:  '<b>Abstarct</b>: Bayesian optimization is widely used for black-box function optimization, excelling in global optimization and minimal sample requirements. It's valuable for complex, non-convex, and computationally expensive problems, prevalent in machine learning and optimization. Traditional Bayesian optimization relies on Gaussian processes, which face limitations in computational cost and scalability. We introduce a Transformer-based Bayesian optimization approach, <b>merging Gaussian process uncertainty estimation with neural network scalability</b>. This approach, incorporating self-attention mechanisms for better contextual integration, <b>outperforms traditional methods</b>, delivering similar optimization performance as Gaussian processes but with significantly <b>faster processing times (O(n^1.41)</b> for PT-BO and O(n^2.16) for GP-BO). Moreover, experiments show Transformer-based Bayesian optimization to be <b>more efficient for high-dimensional data or large datasets</b>, with higher optimization efficiency compared to GP-BO.'
date: 2023-06-24
citation: 'Cheng Ma, <b>Peiqi Yu</b>, Jiwen Lu, Jie Zhou.'
img: "/images/TIP2022graph.png"
---

<b>Abstract:</b>
The emergence of implicit neural representations (INR) has shown the potential to represent images in a continuous form by mapping pixel coordinates to RGB values. Recent work is capable of recovering arbitrary-resolution images from the continuous representations of the input low-resolution (LR) images. However, it can only super-resolve blurry images and lacks the ability to generate perceptual-pleasant details. In this paper, we propose implicit pixel flow (IPF) to model the coordinate dependency between the blurry INR distribution and the sharp real-world distribution. For each pixel near the blurry edges, IPF assigns offsets for the coordinates of the pixel so that the original RGB values can be replaced by the RGB values of a neighboring pixel which are more appropriate to form sharper edges. By modifying the relationship between the INR-domain coordinates and the image-domain pixels via IPF, we convert the original blurry INR distribution to a sharp one. Specifically, we adopt convolutional neural networks to extract continuous flow representations and employ multi-layer perceptrons to build the implicit function for calculating pixel flow. In addition, we propose a new double constraint module to search for more stable and optimal pixel flows during training. To the best of our knowledge, this is the first method to recover perceptually-pleasant details for magnification-arbitrary single image super-resolution. Experimental results on public benchmark datasets demonstrate that we successfully restore shape edges and satisfactory textures from continuous image representations.

<b>My contribution:</b>
1. Proposed feature aggregation, designed confidence module and implemented main codes, achieving a SOTA infinite image super-resolution model.
2. Conducted all comparison experiments and ablation studies to form Fig.2, Fig.4$\sim$7, Fig.9$\sim$10, Fig.13, TABLE I$\sim$III.


<td><img class="proj_thumb" src="images/TIP2022graph.png" width="700px" alt=""/>&nbsp;</td>

[Download paper here](http://patricia1019.github.io/files/TIP2022.pdf)

