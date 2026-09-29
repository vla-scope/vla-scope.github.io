# VLA-Scope Project Website

Source for [vla-scope.github.io](https://vla-scope.github.io/).
The research-code repository is [vla-scope/Scope](https://github.com/vla-scope/Scope).

## Editing and deployment

- `docs/index.html`: page content.
- `docs/style.css`: custom styling.
- `docs/assets/`: figures, videos, and paper PDF.
- `docs/static/`: template styles and third-party license notices.

GitHub Pages publishes `docs/` from the `main` branch. No build step is required.

## Local preview

From the repository root, run:

```sh
python -m http.server 8000 --bind 127.0.0.1 --directory docs
```

Open <http://127.0.0.1:8000/>.

## Attribution and license

Adapted from the [Nerfies website template](https://github.com/nerfies/nerfies.github.io/tree/657409a62d59a93163872c0e4921cf651b987810), with VLA-Scope content and custom layout styling. The adapted HTML and CSS are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Bulma retains its [MIT license](docs/static/css/BULMA-LICENSE.txt).

These template licenses do not cover the paper, research figures, videos, or the separate research-code repository.
