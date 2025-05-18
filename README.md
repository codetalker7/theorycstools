# Math/Theory CS Tools

This is a series of blogs which I'm planning to write on various theoretical
tools/techniques that I find interesting. I've written about the point of these
blogs [on my website](), and I'm too lazy to write those points here. This
repository is based on the [bookdown](https://bookdown.org/yihui/bookdown/)
package, enabling one to write books in R Markdown. I'd love new PRs to this
repository (if someone has related ideas of things that can go here).

## Usage

To render the book, do this from the `R` console:

```{r, eval=FALSE}
bookdown::render_book()
```

A local server can also be started to preview the notes as an HTML book. This
also supports dynamic updates:

```{r eval=FALSE}
bookdown::serve_book()
```

To stop the server:

```{r eval=FALSE}
servr::daemon_stop(1)
```

