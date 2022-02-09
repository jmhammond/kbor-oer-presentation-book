# Sample Book For KBOR OER Presentation

This is the sample book that I'm including for source examples in my presentation on PreText for the [KBOR OER Conference](https://www.kansasregents.org/academic_affairs/open-educational-resources/oer-conference)


A live version of this book is residing (at least temporarily) [on my website](https://hammond.math.wichita.edu/kbor-oer/frontmatter.html). You can access the [generated pdf here as well](https://hammond.math.wichita.edu/kbor-oer/main.pdf).


## Building the Book:

In order to generate the `tikz` graphs, you need to, at least once, run `pretext build html -d`. The `-d` flag tells PreText to build the **d**iagrams from the LaTeX code.

### HTML 

To build the book as an interative webpage, run:

```bash
pretext build html
```

followed by 

``` bash
pretext view html
```

If you want pretext to keep looking for changes and update the webpages automatically, instead run 

``` bash
pretext view html --watch
```


### PDF 

As a $\LaTeX$ pdf, use:

``` bash
pretext build pdf
```
You can then either open the PDF (which you find in the `output/pdf/` folder) in your file browser, or use `pretext view pdf` to view the pdf in your browser.

Note that you don't need to specify latex to build diagrams, because latex knows how to handle the tikz diagrams automatically.

### Additional build options

Explore the [PreText Author Guide documentation](https://pretextbook.org/doc/guide/html/processing-publisher-stringparam.html) to see more options (there's a lot you can do!)

### FYI about the color scheme
 
... by the way, you might have noticed that the color is different than if you built your own sample book. The default color scheme is blue and red, but since I'm from the wheat-based school, I prefer brown and gold (closest to Shocker Colors).

This is controlled in the `publication/publication.ptx` file `css style` tag.
