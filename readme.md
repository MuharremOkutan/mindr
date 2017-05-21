# R package mindr: convert markdown (.md) or rmarkdown (.Rmd) files to mind maps, and vice versa

## Quick start

### Installation

```
devtools::install_github("pzhaonet/mindr")
```

### Create a mindmap from (a) markdown file(s).

Create a folder named `mm` in the working directory (`getwd()`), and drop some markdown or rmarkdown files into `mm/`. Run: 

```
mindr::mindr()
```

then you will get a `mm.mm` file. Open it with any mind-map (brainstorm) software, and you will get a mind map.

Plenty of cross-platform and online mindmap software suits are available (see [the list](https://en.wikipedia.org/wiki/List_of_concept-_and_mind-mapping_software)), among which [freemind](http://freemind.sourceforge.net/wiki/index.php/Download) and [Xmind](http://www.xmind.net/download/win/) are highly recommended.

### Create a markdown file from (a) mind map(s).

Drop some mindmap files (.mm) into `mm/`. Run: 

```
outline(inputformat = 'mindmap', savefile = TRUE)
```

then you will get a markdown file.

Have fun!

Still being developed. Feel free to give your feedback to me!

## Showcase

- Mindmap of [bookdown manual](https://github.com/rstudio/bookdown/tree/master/inst/examples)

![](https://raw.githubusercontent.com/pzhaonet/mindr/master/showcase/mindr_bookdown.jpeg)

- Mindmap of [blogdown manual](https://github.com/rstudio/blogdown/tree/master/docs)

![](https://raw.githubusercontent.com/pzhaonet/mindr/master/showcase/mindr_blogdown.jpg)

- Mindmap of my book *Learning R*

![](https://raw.githubusercontent.com/pzhaonet/mindr/master/showcase/mindr_xuer.jpg)

## Updates

- 2017-05-21. **Version 0.1.0**. Bidirectional! Now mind maps can be converted to markdown.
- 2017-05-20. **Version 0.0.1**. Can Save the outline.
- 2017-05-19. **Version 0.0.0**. A very preliminary version.

# License

Copyright 2017 [Peng Zhao](http://pzhao.org).

Released under the [MIT](https://github.com/pzhaonet/bookdown-plus/blob/master/LICENSE.md) license.

