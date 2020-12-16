Yapeng Shi's resume generated via latex.

### Build CV using Docker and [latex]

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex Yapeng_Resume.tex
```

### Preview

Yapeng_Resume.png

### License

Format is MIT but all the data is owned by Yapeng Shi.
