# Posters

Required fonts:
- Allegre Sans
- Futura LtCn BT
- sans-serif


Converting RGB pdf to CMYK pdf:
```
$ gs \
  -o poster-cmyk.pdf \
  -sDEVICE=pdfwrite \
  -sProcessColorModel=DeviceCMYK \
  -sColorConversionStrategy=CMYK \
  -sColorConversionStrategyForImages=CMYK \
   poster-rgb.pdf 
```
