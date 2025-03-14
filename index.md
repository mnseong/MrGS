---
layout: project_page
permalink: /

title: "MrGS: Multi-modal Radiance Fields with 3D Gaussian Splatting for RGB-Thermal Novel View Synthesis"
authors: Minseong Kweon<sup>1</sup>, Janghyun Kim<sup>1</sup>, Ukcheol Shin<sup>2</sup>, Jinsun Park<sup>1</sup>
affiliations: Pusan National University<sup>1</sup>, Carnegie Mellon University<sup>2</sup>
paper: https://mnseong.github.io/MrGS
code: https://mnseong.github.io/MrGS
---

![NoiseGS-Teaser](/static/image/MainArch.png)
_**Fig. 1.** Overall framework of the proposed MrGS. MrGS framework simultaneously renders RGB and thermal images from 3D Gaussians._

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Recent advances in Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting (3DGS) have significantly improved the RGB scene reconstruction quality. However, multi-modal scene rendering, particularly incorporating thermal imagery, remains largely unexplored. Existing methods often overlook unique thermal characteristics, such as heat conduction and view-independent reflection. In this paper, we propose MrGS, the first multi-modal radiance field in 3DGS that simultaneously reconstructs scenes from both RGB and thermal modalities. Specifically, MrGS employs a multi-modal appearance embedding and an orthogonal feature extraction module to capture the characteristics of two independent modalities (i.e., color and temperature) for the same 3D scene within a single latent space. In addition, we integrate two physics-based principles to precisely model the behavior of the thermal domain: i) We incorporate Fourier’s law of heat conduction into 3D Gaussians to model heat transfer between neighboring Gaussians prior to alpha blending. ii) We apply the Stefan–Boltzmann law and the inverse-square law to formulate a depth-aware thermal radiation map, imposing additional geometric constraints for thermal rendering. Experimental results demonstrate that the proposed MrGS achieves high-fidelity multi-modal scene reconstruction and effectively captures the distinct characteristics of both RGB and thermal domains while using a small number of Gaussians.
        </div>
    </div>
</div>

---

> Note: This project is currently under review at a double-blind conference.

## Qualitative Results

![comparison](/static/image/q_result.png)

_**Fig. 2.** Qualitative highlights for RGB-Thermal novel view synthesis._

## Ablation studies

![ablation](/static/image/ab.png)

_**Fig. 3.** Effectiveness of the proposed depth-aware thermal radiation learning with an uncertainty._

## Citation

```
Will be updated soon
```
