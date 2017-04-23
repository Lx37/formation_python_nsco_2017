lancer:
```
pandoc -t slidy -s slides.md  -o slides.html
```
ou bien
```
pandoc -t beamer -s slides.md  -o slides.pdf
```

pandoc -t revealjs -s --standalone --section-divs -V theme=white -V transition=concave --include-in-header mycss.css -o slides.html slides.md


