# quarto-analytics-template

Hello, Quarto: A World of Possibilities (for Reproducible Publishing)

## Setup notes for FIN7028

- Access to [Q-RaP FIN7028 financial time series workspace](https://sso.posit.cloud/q-rap?redirect=https%3A%2F%2Fposit.cloud%2Fspaces%2F211210%2Fjoin%3Faccess_code%3D0jJzcGhdja1HwVVMRYY-FZRlTIg8XNyvt7XzPw7g)
- Packages: tidyverse, plotly, tsfe

## Setup notes for FIN7030

- Access to [Q-RaP FIN7030 financial time series workspace](https://sso.posit.cloud/q-rap?redirect=https%3A%2F%2Fposit.cloud%2Fspaces%2F211210%2Fjoin%3Faccess_code%3D0jJzcGhdja1HwVVMRYY-FZRlTIg8XNyvt7XzPw7g)
- Packages: tidyverse, plotly, fml
- A working OpenAI API key

### To get you started with quarto

* [Quarto Introduction Tutorial](https://quarto.org/docs/get-started/hello/rstudio.html)
* [A Quarto tip a day](https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/)
* [Quarto Cheatsheet](./Quarto_Cheat_Sheet.pdf)
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

## AI policy

If you use AI (for example ChatGPT, GPT-3, Codex etc ..) in this class, you **must** create a section in your Appendix entitled **My AI use explained**, see details below.  Students' most use GitHub for their project, and misuse of AI will be presumed if students' fail to stage-committ-push regular updates before they submit their final project.

Be aware of the limits of ChatGPT:

* If you provide minimum effort prompts, you will get low-quality results. You'll need to refine your prompts so you can get good outcomes. This will take work.
* Don't trust anything it says. If it gives you several facts, assume it is wrong unless you know the answer or can check in with another source. You will be responsible for any errors or omissions the tools provide. It works best for topics you understand.
* AI is a tool, but one that you should acknowledge using. Please include a paragraph at the end of the assignment that uses AI explaining what you used the AI for and what prompts you used to get results. Failure to do so is a violation of academic honesty policies.
* Be thoughtful about when this tool is useful. Don't use it if it isn't appropriate for the case or circumstance.