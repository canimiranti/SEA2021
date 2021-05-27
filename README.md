# template-xaringanthemer-slides
t
## How to create PDF slides

### Manually

Various approaches exist converting HTML slides to PDF. One way is to print the slides to PDF using your web browser (e.g. Ctrl + P or Command + P in Google Chrome). Firefox is not supported, Chrome should work best.

### With a package: Currently not working well

```
library(webshot)
webshot::install_phantomjs(force = TRUE)
```
```
library(webshot)
webshot("index.html", "index.pdf")
```

Currently not working well