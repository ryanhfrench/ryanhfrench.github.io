---
title: "Analyzing Key Indicators of Positive Reviews for iOS Apps"
date: 2019-04-21
tags: [data science, machine learning, apple, iOS, random forest]
header:
  image: "/images/perceptron/abstract-curves-led-1944.jpg"
excerpt: "My final project for Scripting for Data Analysis"
mathjax: "true"
---

## Project Overview
Recently the first company to reach 1 trillion dollars in valuation, Apple has
undoubtedly cemented itself as the tech giant of our time. With one of the most
profitable (and closely regulated) app stores in the world, I was interested to
see whether or not I could build a predictive model capable of classifying
highly rated apps (above a 4/5).

## Data Source
[link](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps)?

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$
