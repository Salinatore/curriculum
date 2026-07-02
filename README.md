# CV

My CV, written in YAML and built with [RenderCV](https://docs.rendercv.com). The latest version is always available on GitHub Pages [here](https://salinatore.github.io/curriculum/cv.pdf).

## Updating the CV

1. Edit `cv.yaml`.
2. Render locally to check it before pushing:
   ```bash
   uv tool install "rendercv[full]"
   rendercv render file_name.yaml --watch
   ```
   This creates `rendercv_output/` with the PDF, HTML, Typst source, and a PNG preview. 
