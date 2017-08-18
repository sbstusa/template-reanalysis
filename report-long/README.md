Here you can find resources for making long reports which require multiple analysis files.

To compile in R use `render()`. 

To compile at the unix command line with pandoc installed (on a Mac right now):

```
/usr/local/bin/pandoc +RTS -K512m -RTS report-long.Rmd --to latex --from markdown+autolink_bare_uris+ascii_identifiers+tex_math_single_backslash --output report-long.tex --template reportlong.latex --highlight-style tango --latex-engine /Library/TeX/texbin/xelatex --biblatex --include-in-header defs-all.sty --bibliography refs.bib

latexmk -pdflatex='xelatex --shell-escape' -pdf report-long.tex
```

