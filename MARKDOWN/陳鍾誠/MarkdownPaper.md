```
pandoc --filter pandoc-citeproc --bibliography=paper.bib --variable classoption=twocolumn --variable papersize=a4paper -s cpaper.md -o cpaper.pdf --pdf-engine=xelatex -V mainfont='SimSun'
```

```
pandoc --filter pandoc-citeproc --bibliography=paper.bib --variable classoption=twocolumn --variable papersize=a4paper -s cpaper.md -o cpaper.pdf --pdf-engine=xelatex -V mainfont="Microsoft JhenHei"
```

```
pandoc --filter pandoc-citeproc --bibliography=paper.bib --variable classoption=twocolumn --variable papersize=a4paper -s epaper.md -o epaper.pdf
```