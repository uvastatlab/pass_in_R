# Power and Sample Size in R

This is a project of the UVA Library StatLab to document examples of estimating power and sample size in R for various statistical tests and comparisons. It is a work in progress.

View book: [https://uvastatlab.github.io/pass_in_R/](https://uvastatlab.github.io/pass_in_R/)

# Contribution guide and notes

- To start a new chapter, File...New...Quarto Document, click Create Empty Document. Fill in chapter title in the header and save file to root directory. Add file name to _quarto.yml.
- Examples should get a level 3 header. For example: `### Example: sample size`
- To view additions/changes locally, click Render.
- Any R packages required should be listed in the DESCRIPTION file under Imports.
- References should be added to references.bib in BibTeX format. To use a reference in a qmd file, use `[@name]`, where "name" is the citekey that follows immediately after the opening bracket of the BibTeX entry.
- The book is published using a GitHub Action that automatically renders the files and publishes the content whenever you push a change to the repository.
- The GitHub Action is defined in the publish.yml file in `.github/workflows` folder. It was created using information from [this video](https://www.youtube.com/watch?v=arzBRW5XIkg) and the [build_book.yaml](https://github.com/hadley/r4ds/blob/main/.github/workflows/build_book.yaml) file from the R4DS repo.
- GitHub commands:
    * Clone the repo: `git clone git@github.com:uvastatlab/pass_in_R.git`
    * Pull latest updates from GitHub: `git pull origin main`
    * Add all files to next commit: `git add .`
    * Commit changes: `git commit m "message describing changes"`
    * Push updates to GitHub: `git push origin main`
