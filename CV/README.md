Yapeng Shi's resume generated via latex.

### Build CV using Docker and [latex]

```sh
sudo docker build -t latex:full .
docker run --rm -ti -v "$PWD":/data latex:full pdflatex Yapeng_Resume.tex
evince Yapeng_Resume.pdf  # view CV
```
