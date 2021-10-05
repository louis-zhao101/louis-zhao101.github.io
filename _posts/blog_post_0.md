---
layout: post
title: Example post
---

The goal of this blog post is to create a tutorial on generating a visualization for the penguins dataset

###Reading the Dataset

First let's read in our dataset and take a look at the first 5 rows to get a better sense of what it looks like

```python
import pandas as pd
url = "https://raw.githubusercontent.com/PhilChodrow/PIC16B/master/datasets/palmer_penguins.csv"
penguins = pd.read_csv(url)
penguins.head()
```