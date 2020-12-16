Yapeng Shi's resume generated via latex.

### Build CV using Docker [latex version]

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex Yapeng_Resume.tex
```

### Preview

![Resume Screenshot](/Yapeng_ Resume.png)

### License

Format is MIT but all the data is owned by Yapeng Shi.
