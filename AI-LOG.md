# AI log

One entry per piece of work where an AI assistant helped: what you asked, what you kept, what you
changed, and how you checked. Short and factual. Use you did not record, or results you cannot
explain, lose points (course syllabus, "Using AI").

## [date] · [what you were doing]

- **Tool:** [assistant and, if you know it, the model]
- **Prompt:** "[the key prompt, or a short summary of a longer exchange]"
- **Accepted:** [what you used as it came]
- **Rejected or corrected:** [what was wrong, and what you did instead]
- **Checked:** [how you know the result is right: counts, totals, a recomputed number, the docs]

<!-- An example of a finished entry (delete it when you write your own):

## 2026-10-30 · the first version of graph 1

- **Tool:** ChatGPT (GPT-5)
- **Prompt:** "Using ggplot2 and the mpg data, draw highway mileage (hwy) for each car class as box
  plots, classes ordered by their median, axis titles in plain words with units."
- **Accepted:** the boxplot and reorder(class, hwy, FUN = median).
- **Rejected or corrected:** it mapped cty instead of hwy; I changed it. It used a rainbow fill for
  the classes; I removed it, because the position already names the class.
- **Checked:** compared the median of two classes with dplyr::summarise(); 2seater and SUV match the plot.
-->
