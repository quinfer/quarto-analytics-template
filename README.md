# quarto-analytics-template

Hello, Quarto: A World of Possibilities (for Reproducible Publishing)

## Setup notes

- Access to [q-rap FIN7028 financial time series workspace](https://sso.posit.cloud/q-rap?redirect=https%3A%2F%2Fposit.cloud%2Fspaces%2F211210%2Fjoin%3Faccess_code%3D0jJzcGhdja1HwVVMRYY-FZRlTIg8XNyvt7XzPw7g)
- Packages: tidyverse, plotly, tsfe

### To get you started with quarto

* [R Markdown Quick Tour](https://rmarkdown.rstudio.com/authoring_quick_tour.html)
* [Introduction to R Markdown](https://rmarkdown.rstudio.com/lesson-1.html)
* [R Markdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
- Create a simple Quarto document called `index.qmd` and edit it using the RStudio Visual Editor with sections 

## Demo

### Documents
1. Create a simple Quarto document called `index.qmd` and edit it using the RStudio Visual Editor with sections Introduction and Critique, Data amd Methods, Results, and Discussions
2. Add code chunk options:
  - `echo: false` in `execute` in the YAML
  - `code-fold`
  - `fig-alt`
  - teaching tip: `echo: fenced`
3. Add a figure and a table and cross reference them
3. Add a citation

> **Tip**: It is good practice to HIT and KNIT every time you do a new piece of code or text chunk

### To get you started with R markdown

* [R Markdown Quick Tour](https://rmarkdown.rstudio.com/authoring_quick_tour.html)
* [Introduction to R Markdown](https://rmarkdown.rstudio.com/lesson-1.html)
* [R Markdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
- Create a simple Quarto document called `index.qmd` and edit it using the RStudio Visual Editor with sections 

### Slides

- Change `format: revealjs`
- Add section headings: First level headings Introduction and Analysis, under Analysis a second level heading called Modeling
- Add columns to slides
- Reveal code with `echo: true`
  - teaching-tip: `code-line-numbers`
- Change `output-location` of figure

### Websites

- Add another document `about.qmd`
- Add `quarto.yml` 

```
project:
  type: website

website:
  title: "Hello Quarto - Website"
  navbar:
    left:
      - index.qmd
      - about.qmd
```

- Render and then `publish quarto`