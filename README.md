# PS7 — Data exploration and analysis

Repeat the tutorial workflow on **a new dataset of your choice**: inspect, plot histograms / scatter plots, and write a short analysis of one figure.

**Due (Odyssey):** 03/12/2026 at 08:00 (Asia/Jerusalem).

> **Important — manual grading**  
> There is **no autograder** this week and **no green ✓** is expected.  
> We will review your repository **manually** (code + figure + short analysis).

## What to do

1. Choose a dataset (`sklearn`, Kaggle, or any open dataset).
2. Repeat the tutorial steps: load/inspect, select features, histograms, scatter plots, correlation scatter plot.
3. Upload to GitHub:
   - `main.py` — your analysis code
   - a figure file (e.g. `correlation.png`)
   - `analysis.txt` — fill the template (see below)

## `analysis.txt` template

Start from the starter file `analysis.txt` and answer **each numbered question**.

| # | Question | Length |
|---|----------|--------|
| 1 | Dataset / data source | short |
| 2 | What did you import / use? | short |
| 3 | Which variables are on the graph? | short |
| 4 | Which plotting functions did you use (and why)? | short |
| 5 | **Graph analysis** — what the figure shows | **max 2 lines** |

Only section **5** is limited to ~2 lines. Sections 1–4 are separate answers (still keep them concise).

A filled illustration is in `analysis_example.txt` (do **not** submit that file — it is only an example).

### Example (same content as `analysis_example.txt`)

```text
1) Dataset / data source:
   OpenML diabetes (same family of data as in the tutorial).

2) What did you import / use?
   pandas; matplotlib.pyplot as plt; (optional) seaborn as sns.

3) Which variables are on the graph?
   x = Glucose, y = BMI; points colored by Diabetes (positive / negative).

4) Which plotting functions did you use (and why they help)?
   plt.scatter(..., c=...) to separate outcomes by color; plt.xlabel / plt.ylabel for clear axes;
   optional sns.regplot to show a trend line.

5) Graph analysis (max 2 lines):
   Higher Glucose often appears with higher BMI, especially among positives.
   The two outcome groups overlap, but positives tend to sit further up/right.
```

## Optional: improve the figure with AI

Ask an AI assistant for one or a few improvements (fonts, regression line, Seaborn/Plotly style, boxplot, …), and mention them briefly in question 4.

## Submit

1. Accept the Classroom 50 assignment.
2. Add/commit `main.py`, filled `analysis.txt`, and your figure.
3. **Do not wait for a green ✓** — none is expected; submission is complete once the files are in the repo.

## Checklist

- [ ] `main.py`
- [ ] figure (e.g. `correlation.png`)
- [ ] `analysis.txt` filled (questions 1–5; analysis ≤ 2 lines)
- [ ] no green ✓ required (manual check)
