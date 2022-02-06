# Sample Book For KBOR OER Presentation

This is the sample book that I'm including for source examples in my presentation on PreText for the [KBOR OER Conference](https://www.kansasregents.org/academic_affairs/open-educational-resources/oer-conference)

## Building the Book:

### HTML 

To build the book as an interative webpage, run:

```bash
pretext build html
```

followed by 

``` bash
pretext view html
```

### PDF 

As a $\LaTeX$ pdf, use:

``` bash
pretext build pdf
```
You can then either open the PDF (which you find in the `output/pdf/` folder) in your file browser, or use `pretext view pdf` to view the pdf in your browser.


### Additional build options

Explore the [PreText Author Guide documentation](https://pretextbook.org/doc/guide/html/processing-publisher-stringparam.html) to see more options (there's a lot you can do!)

### FYI about the color scheme
 
... by the way, you might have noticed that the color is different than if you built your own sample book. The default color scheme is blue and red, but since I'm from the wheat-based school, I prefer brown and gold (closest to Shocker Colors).

This is controlled in the `publication/publication.ptx` file `css style` tag.
