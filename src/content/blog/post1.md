---
title: "Demo Post 1"
description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
pubDate: "Sep 10 2022"
heroImage: "/post_img.webp"
tags: ["CNN"]
layout: '../../layouts/MarkdownLayout.astro'
---
At each layer of a convolutional network, a collection of filters expresses local spatial connection patterns along the input channels. This enables CNNs to capture hierarchical patterns and create globally theoretically relevant fields. The convolutional filters create the feature maps using the learned weights in those filters. The filters collectively learn as they analyze the image various feature representations of the target class information included in the image encoded by the input tensor. Some filters pick up edges, while others pick up textures.

One main problem with such operation is while getting output from the input, we assume each channel is equal in importance. In this article, we examine one use of a novel architecture that Hu et al. [^1] described in their study, "Squeeze-and-Excitation." Squeeze-and-Excitation Networks (SENet) explicitly model the dependencies between the channels of a network's convolutional features in order to improve the quality of representations produced by the network.

In order to adjust features for SENet to enhance informative parts while suppressing less valuable ones, the network employs a self-attention approach.

The mathematical equation can be represented as:

$$
\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\ldots} } } }
$$

One main problem with such operation is while getting output from the input, we assume each channel is equal in importance. In this article, we examine one use of a novel architecture that Hu et al. [1] described in their study, "Squeeze-and-Excitation." Squeeze-and-Excitation Networks (SENet) explicitly model the dependencies between the channels of a network's convolutional features in order to improve the quality of representations produced by the network.
In order to adjust features for SENet to enhance informative parts while suppressing less valuable ones, the network employs a self-attention approach.

I love $M$ self

$$
L = \frac{1}{2} \rho v^2 S C_L
$$

## 2- Squeeze-and-Excitation Blocks (SE Blocks)
A Squeeze-and-Excite block is a brand-new, simple-to-plug-in module.

A Squeeze-and-Excitation block can be built on the top of a transformation $x^2$ mapping an input X to features U by using a set of filters V.
We can write output filters as :

[^1]: Hu, J., Shen, L., & Sun, G. (2018). Squeeze-and-Excitation Networks. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 7132-7141).
