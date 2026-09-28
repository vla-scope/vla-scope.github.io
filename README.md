# VLA-Scope

**Shift-Aware Failure Prediction for Vision-Language-Action Models**

Kaiwen Zhu, Dongfang Liu, and Liangkai Liu

[Project website](https://vla-scope.github.io/) · [Paper](https://arxiv.org/abs/2609.21246)

VLA-Scope connects initial input-shift characterization with failure prediction from partial executions. It combines predicted OOD type, action-prefix features, and cumulative execution-step representations while keeping the underlying VLA policy frozen.

## Repository status

This repository contains only the project website and demonstration videos. The main project repository is [vla-scope/Scope](https://github.com/vla-scope/Scope). Research code has not yet been released.

## Website

The static website is in `docs/`, including its local images, videos, and paper PDF. GitHub Pages publishes the `docs/` directory from the `main` branch. No build dependencies or external scripts are required.

To preview locally, run `python -m http.server 8000 --bind 127.0.0.1 --directory docs` and visit `http://127.0.0.1:8000/`.

## Demonstrations

The videos show selected illustrative cases, not an unbiased sample of performance. Risk scores are unchanged. Success/Failure labels indicate final rollout outcomes; colored borders indicate current risk relative to the 0.5 threshold.

## Website template and license

The website is adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io), revision `657409a62d59a93163872c0e4921cf651b987810`.
It reuses the template's Bulma-based hero/column layout, publication title and author structure, teaser structure, footer structure, and a trimmed subset of its `static/css/index.css` in `docs/static/css/nerfies.css`.
VLA-Scope content, responsive styling, tables, and local videos replace the original demonstrations. The custom stylesheet preserves our existing page dimensions and typography. No Nerfies analytics, JavaScript, or research media are included.

The adapted website template (HTML and custom CSS) is distributed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). Bulma 0.9.1 retains its MIT license; see `docs/static/css/BULMA-LICENSE.txt`. The website-template license does not relicense the paper, research figures, videos, or the separate Scope research-code repository.
