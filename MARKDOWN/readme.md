# Script
## 無中文
pandoc --filter pandoc-citeproc --bibliography=paper.bib --variable classoption=twocolumn --variable papersize=a4paper -s paper.md -o paper2.pdf

## 有中文
pandoc --filter pandoc-citeproc --bibliography=paper.bib --variable classoption=twocolumn --variable papersize=a4paper -s cpaper.md -o cpaper.pdf --pdf-engine=xelatex -V mainfont="Microsoft JhengHei"