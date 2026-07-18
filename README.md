# CV

My CV, written in YAML and built with [RenderCV](https://docs.rendercv.com). The latest versions are always available on GitHub Pages:

- Italian: [cv-it.pdf](https://salinatore.github.io/curriculum/cv-it.pdf) (also aliased at [cv.pdf](https://salinatore.github.io/curriculum/cv.pdf))
- English: [cv-en.pdf](https://salinatore.github.io/curriculum/cv-en.pdf)

## Updating the CV

1. Edit `Alessandro_Gardini_CV_IT.yaml` and/or `Alessandro_Gardini_CV_EN.yaml`.
2. Render locally to check it before pushing:
   ```bash
   uv tool install "rendercv[full]"
   rendercv render Alessandro_Gardini_CV_IT.yaml --watch
   rendercv render Alessandro_Gardini_CV_EN.yaml --watch
   ```
   This creates `rendercv_output/` with the PDF, HTML, Typst source, and a PNG preview.