---
title: "Automatic surface segmentation for seamless fabrication using 4-axis milling machines"
description: "4-axis milling"
---

Stefano Nuvoli (a), Alessandro Tola (a), Alessandro Muntoni (b), Nico Pietroni (c), Enrico Gobbetti (d), Riccardo Scateni (a)

Computer Graphics Forum, Vol 40(2), 2021 (Eurographics 2021, Vienna Austria)

(a): *Department of Mathematics and Computer Science, University of Cagliari, Cagliari, Italy*

(b): *Visual Computing Laboratory, ISTI-CNR, Pisa, Italy*

(c): *University of Technology Sydney, Australia*

(d): *CRS4, Cagliari, Italy*

![4axismilling](/images/4axismilling_teaser.png)

## Abstract

We introduce a novel geometry-processing pipeline to guide the fabrication of complex shapes from a single block of material
using 4-axis CNC milling machines. This setup extends classical 3-axis CNC machining with an extra degree of freedom to rotate
the object around a fixed axis. The first step of our pipeline identifies the rotation axis that maximizes the overall fabrication
accuracy. Then we identify two height-field regions at the rotation axis’s extremes used to secure the block on the rotation
tool. We segment the remaining portion of the mesh into a set of height-fields whose principal directions are orthogonal to the
rotation axis. The segmentation balances the approximation quality, the boundary smoothness, and the total number of patches.
Additionally, the segmentation process takes into account the object’s geometric features, as well as saliency information. The
output is a set of meshes ready to be processed by off-the-shelf software for the 3-axis tool-path generation. We present several
results to demonstrate the quality and efficiency of our approach to a range of inputs.

## Downloads


| &nbsp;&nbsp;&nbsp; Paper: &nbsp;&nbsp;&nbsp;	| &nbsp;&nbsp; Results: &nbsp;&nbsp;	| Source code: 	|
|:------:	|:--------:	|:------------:	|
| [![pdf](/images/pdf.png)](/data/4axis.pdf) | [![zip](/images/zip.png)](https://github.com/cg3hci/4AxisMilling/releases/tag/v1.0) | [![github](/images/github.png)](https://github.com/cg3hci/4AxisMilling) |

## Video

{{< youtube V5kCuFqoWLw >}}

## BibTex

```
@Article{Nuvoli:2021:ASS,
    author = {Stefano Nuvoli and Alessandro Tola and Alessandro Muntoni and Nico Pietroni and Enrico Gobbetti and Riccardo Scateni},
    title = {Automatic Surface Segmentation for Seamless Fabrication using 4-axis Milling Machines},
    journal = {Computer Graphics Forum},
    volume = {40},
    number = {2},
    year = {2021},
    doi = {10.1111/cgf.142625},
    note = {To appear},
}
```
