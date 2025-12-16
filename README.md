# Personal Website - Yongyan Liu

This repository contains the source code for my personal website, hosted on [GitHub Pages](https://pages.github.com/). It serves as a personal archive and portfolio, showcasing my academic journey in Biostatistics, data analysis projects, and personal interests like skiing and scuba diving.

## Project Structure

*   **`index.Rmd`**: The main RMarkdown source file that generates the homepage.
*   **`_site.yml`**: Configuration file for the RMarkdown website, defining the navigation bar and output settings.
*   **`photos/`**: Directory containing personal photos used on the website.
*   **`resumes/`**: Directory for storing my curriculum vitae.
*   **`index.html`**: The generated HTML file (do not edit this directly; edit `index.Rmd` instead).

## How to Build

This website is built using [RMarkdown](https://rmarkdown.rstudio.com/).

1.  Open the project in RStudio (`liuyongyan.github.io.Rproj`).
2.  Open `index.Rmd`.
3.  Click the "Knit" button to generate the HTML output.
    *   Alternatively, run `rmarkdown::render_site()` from the R console.

## Updates

To update the content:
1.  Modify `index.Rmd` or add new files.
2.  Re-knit the document to update `index.html`.
3.  Commit and push changes to GitHub.
