---
layout: default
title: Gotta Grow Fast
---
<h1><em>Gotta Grow Fast</em>: Design and Benchmarking of a Tip Mount for High-Speed Vine Robots</h1>

**Antonio Alvarez Valdivia**<sup>1</sup>, **Robert Reeve**<sup>1</sup>, **Ankush Dhawan**<sup>1,2</sup>, **Ciera McFarland**<sup>3</sup>, **Chad Council**<sup>1</sup>, **Margaret McGuinness**<sup>3</sup>, and **Nathaniel Hanson**<sup>1</sup>

<sup>1</sup>Lincoln Laboratory, Massachusetts Institute of Technology, Lexington, Massachusetts, USA  
<sup>2</sup>Stanford University, Stanford, California, USA  
<sup>3</sup>University of Notre Dame, Notre Dame, Indiana, USA

Correspondence: nhanson2 [@] mit [.] edu

<div style="text-align: center; margin: 20px 0;">
  <video width="100%" controls style="max-width: 1000px;">
    <source src="media/gotta_grow_fast_video_RAL_compressed.mp4" type="video/mp4">
  </video>
</div>

### 3D Preview: Camera Mount

{% include stl-viewer.html src="/media/camera_mount.stl" id="home-camera-mount-viewer" %}

## Abstract

Soft, growing vine robots extend through tip eversion, a mechanism that enables navigation through cluttered environments. However, integrating cameras and other sensors at the tip is uniquely challenging because the material forming the tip is constantly renewed as the robot grows. This continual material turnover, combined with friction between internal layers, added tip weight, and fabric constriction, complicates sensor and tool mounting. These limitations hinder the deployment of vine robots for inspection and search tasks, where rapid growth while carrying tip-mounted sensors is essential.

In this work, we present a triangular roller tip mount that reduces internal resistance during growth by rolling rather than sliding against the robot body. The design was refined through iterative failure analysis, enabling, for the first time, consistent eversion on a TPU-coated ripstop nylon vine robot.

To quantitatively evaluate mount performance, we introduce a custom testbed that isolates tip-mounting effects by measuring tail tension during eversion. Comparative experiments across multiple mount variants, including prior designs, show that our triangular roller mount achieves the lowest tail tension and most repeatable growth performance.

These results establish both a validated tip-mount design and a repeatable benchmarking framework for advancing sensor and tool integration in soft growing robots.

<!-- [Bill of Materials](./BoM.md){: .btn .btn-primary } -->
<!-- [CAD](./Build_Instructions.md){: .btn .btn-primary } -->

<hr>

[Paper on arXiv](https://arxiv.org/abs/2606.06040){: .btn .btn-primary .mr-2 }
[Paper on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11592424/){: .btn .btn-primary }

If you use or reference our design, please include a citation to our paper:

```bibtex
@article{valdivia2026fast,
  author={Valdivia, Antonio Alvarez and Reeve, Robert and Dhawan, Ankush and McFarland, Ciera and Council, Chad and McGuinness, Margaret and Hanson, Nathaniel},
  journal={IEEE Robotics and Automation Letters}, 
  title={Gotta Grow Fast: Design and Benchmarking of a Tip Mount for High-Speed Vine Robots}, 
  year={2026},
  volume={11},
  number={8},
  pages={9827-9834},
  keywords={Design methodology;Robots;Friction;Fabrics;Tail;Contacts;Force;Geometry;Materials;Resistance;Soft robot materials and design;soft robot applications;search and rescue robots;vine robots},
  doi={10.1109/LRA.2026.3709052}}

```