---
layout: post
title: Blog Post 0
---

The goal of this blog post is to create a tutorial on generating a visualization for the penguins dataset

### Reading the Dataset

First let's read in our dataset and take a look at the first 5 rows to get a better sense of what it looks like
TEST TEST TEST

```python
import pandas as pd
url = "https://raw.githubusercontent.com/PhilChodrow/PIC16B/master/datasets/palmer_penguins.csv"
penguins = pd.read_csv(url)
penguins.head()
```
```
|    | studyName   |   Sample Number | Species                             | Region   | Island    | Stage              | Individual ID   | Clutch Completion   | Date Egg   |   Culmen Length (mm) |   Culmen Depth (mm) |   Flipper Length (mm) |   Body Mass (g) | Sex    |   Delta 15 N (o/oo) |   Delta 13 C (o/oo) | Comments                       |
|---:|:------------|----------------:|:------------------------------------|:---------|:----------|:-------------------|:----------------|:--------------------|:-----------|---------------------:|--------------------:|----------------------:|----------------:|:-------|--------------------:|--------------------:|:-------------------------------|
|  0 | PAL0708     |               1 | Adelie Penguin (Pygoscelis adeliae) | Anvers   | Torgersen | Adult, 1 Egg Stage | N1A1            | Yes                 | 11/11/07   |                 39.1 |                18.7 |                   181 |            3750 | MALE   |           nan       |            nan      | Not enough blood for isotopes. |
|  1 | PAL0708     |               2 | Adelie Penguin (Pygoscelis adeliae) | Anvers   | Torgersen | Adult, 1 Egg Stage | N1A2            | Yes                 | 11/11/07   |                 39.5 |                17.4 |                   186 |            3800 | FEMALE |             8.94956 |            -24.6945 | nan                            |
|  2 | PAL0708     |               3 | Adelie Penguin (Pygoscelis adeliae) | Anvers   | Torgersen | Adult, 1 Egg Stage | N2A1            | Yes                 | 11/16/07   |                 40.3 |                18   |                   195 |            3250 | FEMALE |             8.36821 |            -25.333  | nan                            |
|  3 | PAL0708     |               4 | Adelie Penguin (Pygoscelis adeliae) | Anvers   | Torgersen | Adult, 1 Egg Stage | N2A2            | Yes                 | 11/16/07   |                nan   |               nan   |                   nan |             nan | nan    |           nan       |            nan      | Adult not sampled.             |
|  4 | PAL0708     |               5 | Adelie Penguin (Pygoscelis adeliae) | Anvers   | Torgersen | Adult, 1 Egg Stage | N3A1            | Yes                 | 11/16/07   |                 36.7 |                19.3 |                   193 |            3450 | FEMALE |             8.76651 |            -25.3243 | nan                            |
```
