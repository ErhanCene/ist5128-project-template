# [Project title]

IST5128 · Project 1 · [your name(s)]

**Question.** [One or two sentences: what the project asks, and for whom.]

**Data.** [Source, with a link, the licence, and the date you downloaded it.]

**Report.** https://YOUR-USER.github.io/YOUR-REPOSITORY/

## Reproduce it

1. Clone the repository.
2. Install what the code needs: [R packages / Python packages, or the file that lists them].
3. In this folder, run:

   ```bash
   quarto render
   ```

   The report is written to `_output/index.html`.

## Publish it

Every push to `main` publishes the report by itself: the workflow in
`.github/workflows/publish.yml` renders `report.qmd` with Quarto and puts the result on the
`gh-pages` branch, which GitHub Pages serves at the address above. The **Actions** tab shows each
run; the first one takes a few minutes. Packages beyond ggplot2 and rmarkdown (R) or pandas and
plotnine (Python) go one per line in `r-packages.txt` or `requirements.txt`.

You can also publish from your computer, after committing and pushing, in this folder:

```bash
quarto publish gh-pages
```

`_output/` is never committed: the `gh-pages` branch holds the published copy.

## What is where

| Path | What it holds |
|---|---|
| `report.qmd` | the report: question, data, audit, cleaning, graphs with design records, findings |
| `data/raw/` | the files as downloaded, never edited |
| `data/clean/` | the tidy data the graphs use, made by the code |
| `docs/data-dictionary.md` | every variable of the clean data |
| `docs/cleaning-log.md` | every cleaning step, with row counts before and after |
| `design/` | sketches and the versions of each graph |
| `AI-LOG.md` | how AI assistants were used, and how their output was checked |

*Türkçe: Başlıkları ve metni Türkçe yazabilirsiniz; rapor İngilizce ya da Türkçe olabilir.*
