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

Commit and push your work first, then, in this folder:

```bash
quarto publish gh-pages
```

Quarto renders the report and puts it on the `gh-pages` branch; GitHub Pages serves it at the
address above. Run it again after every change you want online. `_output/` is never committed:
the `gh-pages` branch holds the published copy.

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
