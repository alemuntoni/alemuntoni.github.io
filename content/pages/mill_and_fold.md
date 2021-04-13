---
title: "Mill and Fold: Shape Simplification for Fabrication"
description: "Mill and Fold"
---

Alessandro Muntoni (a), Stefano Nuvoli (b), Andreas Scalas (c,d), Alessandro Tola (b), Luigi Malomo (a), Riccardo Scateni (b)

Computer & Graphics, Vol 80, 17-28, 2019

(a): *Visual Computing Laboratory, ISTI-CNR, Pisa, Italy*

(b): *Department of Mathematics and Computer Science, University of Cagliari, Cagliari, Italy*

(c): *IMATI-CNR, Genova, Italy*

(d): *Department of Informatics, Bioengineering, Robotics and System Engineering, University of Genova, Genova, Italy*

![millandfold](/images/millandfold_teaser.png)

## Abstract

We introduce a pipeline for simplifying digital 3D shapes and fabricate them using 2D polygonal flat parts. Our method generates shapes that, once unfolded, can be fabricated with CNC milling machines using special tools called V-Grooves. These tools create V-shaped furrows at given angles depending on the shape of the used tool. Milling the edges of each flat facet simplifies the manual assembly, which consists only in folding adjacent facets at a constrained angle. Our method generates simplified shapes where every dihedral angle between adjacent facets belongs to a restricted set, thus making the assembly process quicker and more straightforward. Firstly, our method automatically computes a simplified version of the input model, using the marching cubes algorithm on the original mesh and iteratively performing local changes on the resulting triangle mesh. The user can then perform an additional manual simplification to remove unwanted facets. Finally, an unfolding algorithm, which takes into account the thickness of the material, flattens the polygonal facets onto the 2D plane, so that a CNC milling machine can fabricate it from a sheet of rigid material.

## Downloads


| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Paper: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	| Additional material: 	|
|:------:	|:--------:	|:------------:	|
| [![pdf](/images/pdf.png)](/data/mill_and_fold.pdf) | [![pdf](/images/pdf.png)](/data/mill_and_fold_am.pdf) |

## Videos

**Assemblage of Moai Model**

{{< youtube 5L9dlEIFPS4 >}}

**Assemblage of Laurana Model**

{{< youtube 0VRL1MSMeck >}}

## BibTex

```
@article{muntoni2019mill,
  title={Mill and Fold: Shape Simplification for Fabrication},
  author={Muntoni, Alessandro and Nuvoli, Stefano and Scalas, Andreas and  and Tola, Alessandro and Malomo, Luigi and Scateni, Riccardo},
  journal={Computers \& Graphics},
  issue_date = {March 2019},
  volume = {80},
  month = may,
  year={2019},
  pages = {17--28},
  numpages = {12},
  url = {https://doi.org/10.1016/j.cag.2019.03.003},
  doi = {10.1016/j.cag.2019.03.003},
  publisher={Elsevier}
}
```
