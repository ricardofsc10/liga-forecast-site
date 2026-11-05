# Fonts

`archivo.woff2` is Archivo (variable: width 62–125%, weight 100–900) by Omnibus-Type, under the
SIL Open Font License 1.1 (`OFL.txt`). It is a Latin subset made with fontTools from
`ofl/archivo/Archivo[wdth,wght].ttf` in the google/fonts repository (downloaded 2026-11-03,
sha256 `0e094a7d3c7c4c25cf1310c4b30014f1dae9332220b1c2c88f4fa996f0b05053`):

```
pyftsubset "Archivo[wdth,wght].ttf" --flavor=woff2 --layout-features='*' \
  --unicodes="U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+20AC,U+2122,U+2190-2193,U+2212,U+2215,U+00D7"
```

The site serves it from `static/fonts/`, never from a font CDN (D-092).
