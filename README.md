# VLA-Scope

**Shift-Aware Failure Prediction for Vision-Language-Action Models**

Kaiwen Zhu, Dongfang Liu, and Liangkai Liu

[Paper](https://arxiv.org/abs/2609.21246)

VLA-Scope connects initial input-shift characterization with failure prediction from partial executions. It combines predicted OOD type, action-prefix features, and cumulative execution-step representations while keeping the underlying VLA policy frozen.

## Repository status

This repository currently contains the project website and demonstration videos. Research code has not yet been released.

## Website

The static website is in `docs/`, including its local images, videos, and paper PDF. GitHub Pages publishes the `docs/` directory from the `main` branch. No build dependencies or external scripts are required.

To preview locally, run `python -m http.server 8000 --bind 127.0.0.1 --directory docs` and visit `http://127.0.0.1:8000/`.

## Demonstrations

The videos show selected illustrative cases, not an unbiased sample of performance. Risk scores are unchanged. Success/Failure labels indicate final rollout outcomes; colored borders indicate current risk relative to the 0.5 threshold.

The website's overall presentation was inspired by the [SAFE project page](https://vla-safe.github.io/), with original HTML and CSS.
