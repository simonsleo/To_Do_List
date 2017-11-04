# CNN Motivation

http://deeplearning.net/tutorial/lenet.html


Convolutional Neural Networks (CNN) are biologically-inspired variants of MLPs. From Hubel and Wiesel’s early work on the cat’s visual cortex [Hubel68], we know the visual cortex contains a complex arrangement of cells. These cells are sensitive to small sub-regions of the visual field, called a receptive field. The sub-regions are tiled to cover the entire visual field. These cells act as local filters over the input space and are well-suited to exploit the strong spatially local correlation present in natural images.

Additionally, two basic cell types have been identified: Simple cells respond maximally to specific edge-like patterns within their **receptive field**. Complex cells have **larger receptive fields** and are **locally invariant** to the exact position of the pattern.

The animal visual cortex being the most powerful visual processing system in existence, it seems natural to emulate its behavior. Hence, many neurally-inspired models can be found in the literature. To name a few: the NeoCognitron [Fukushima], HMAX [Serre07] and LeNet-5 [LeCun98], which will be the focus of this tutorial.

Possible solutions:
HC may act as complex cells, which have large receptive fields. It seems reasonable to place HC in the location of complex cells.
