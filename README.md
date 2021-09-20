# latex-docker
Dockerfile for running LaTeX in containerised environment

## Useage

```bash
docker run -v $PWD:/output --rm latex-docker pdflatex -shell-escape -interaction nonstopmode myfile.tex
```
