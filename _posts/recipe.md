---
layout: post
title: "The Average Best Chocolate Chip Cookies"
date: 2020-04-06
---

<h1>Keywords: NLP, Named Entity Recognition, Python, Baking<h1/>

I am a beginner baker, and the first recipe I wanted to try was a chocolate chip cookies recipe. Chewy chocolate chip cookies are my all-time favorite. I found tons of recipes online that all claim to be the best, ultimate, and perfect recipes you would ever need. I randomly picked one that seemed promising, but I was not very happy with the results. After several attempts, I came up with the idea: what if I wrote some codes and let the computer make a recipe for me?

The basic idea is that I first scrape ‘best’ chocolate chip cookies recipes from different web pages. Then, I build a custom Named Entity Recognition model using spaCy to extract information. The information is organized in Pandas DataFrame. Finally, an ‘average’ best chewy chocolate chip cookies recipe will be calculated.
