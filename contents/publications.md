## SeaSIG

SeaSIG: Underwater 3D Gaussian Splatting via Medium-Radiance Decomposition and Structure-Invariant Guidance

<strong>Accepted by IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026</strong>. [[Code]](https://github.com/LParsee/SeaSIG)

### Abstract

With the rapid development of underwater robots and sensing technologies, underwater 3D scene reconstruction and novel-view synthesis have become increasingly important. However, underwater images are severely degraded by light absorption and scattering, which cause haze and contrast loss, especially at long range. Although 3D Gaussian Splatting (3DGS) provides an efficient scene representation, directly applying it to underwater scenes often results in blurred details in the far-field regions. To mitigate this, previous approaches introduce physics-based medium modeling to improve long-range detail preservation. However, in complex underwater environments, inaccuracies in medium estimation may still affect color consistency and visual fidelity.

To address this challenge, we propose SeaSIG, a self-supervised underwater 3D scene reconstruction framework built on 3D Gaussian Splatting. SeaSIG combines a view-aware Underwater Medium Optic (UMO) model for medium-radiance decomposition with a Structure-Invariant Guidance (SIG) model for medium-robust structural supervision, thereby improving long-range structural detail preservation while maintaining stable color consistency. Experiments on multiple underwater scenes demonstrate the effectiveness of our method. Compared with representative underwater reconstruction baselines, SeaSIG consistently improves novel-view synthesis quality and long-range structural detail preservation, while maintaining competitive color consistency in challenging underwater environments. Our code will be released at [github.com/LParsee/SeaSIG](https://github.com/LParsee/SeaSIG).

### Pipeline

<img src="static/assets/img/seasig/Pipeline.jpg" alt="SeaSIG pipeline" style="width: 100%; max-width: 1100px; display: block; margin: 1rem auto 2rem auto;">

### Experimental Results

<img src="static/assets/img/seasig/Exp.jpg" alt="SeaSIG experimental results" style="width: 100%; max-width: 1100px; display: block; margin: 1rem auto 0 auto;">