---
layout: single
permalink: /datascience/
author_profile: true
---

<head>
	<script>
	  function resizeIframe(obj) {
		obj.style.height = obj.contentWindow.document.body.scrollHeight + 'px';
	  }
	</script>
</head>

@@ The story about me becoming a data scientist comes here

# SwiftPredict

You know _how_ your mobile keyboard suggests you the next word you want to type? There are several algorithms that may be used for that. One option is to presume that next word in a text only depends on a few previous words (a more specific version of [Markov's assumption](https://en.wikipedia.org/wiki/Causal_Markov_condition#:~:text=The%20Markov%20condition%2C%20sometimes%20called,do%20not%20descend%20from%20it.)). Then, given enough information on what words usually appear in the text together, we can predict what the next word is likely to be, based on the preceding few words.

This is a basic description of a predictive ngram model that I implemented as a capstone project for [Data Science Specializaiton](https://www.coursera.org/specializations/jhu-data-science) at Johns Hopkins University, using a data set provided by [SwiftKey](https://www.microsoft.com/en-us/swiftkey?activetab=pivot_1%3aprimaryr2). (ngram is but a sequence of n words together in a text)

- **Technology:** Implemented in R using [quanteda](https://quanteda.io/) package for text mining and [data.table](https://cran.r-project.org/web/packages/data.table/index.html) for data storage and search optimization
- **Data set:** plain text files harvested from Twitter, blogs and news sites
	1. 556 MB
	2. 2.4 million lines of text
	3. 105 million words
- **Model:** [stupid backoff](https://www.aclweb.org/anthology/D07-1090.pdf) using 1- to 6-grams
	1. 22.8% accuracy for top-3 predictions
	2. 20,000 words dictionary
	3. 226 milllion ngrams analyzed
- **Productionalization:** a simple proof-of-concept web app built on [Shiny](https://shiny.rstudio.com/)
	1. 9.5 million ngrams left after pruning the singletons and keeping only top-3 predictions for each history sequence
	2. Response time 22 msec
	3. Uses 219 MB of RAM when running

Feel free to read the (very long) [R notebook](/homepage/_pages/swiftpredict.html) that describes everything I did step by step: exploratory data analysis, model building, selection and evaluation, with plots and code. Or to check out my github repository: [github.com/dmitrytoda/SwiftPredict](https://github.com/dmitrytoda/SwiftPredict). Or to play with the Shiny app right here:

<div class="h_iframe">
	<iframe src="https://dmitrytoda.shinyapps.io/SwiftPredict/" frameborder="0" allowfullscreen scrolling="no" onload="resizeIframe(this)" />
</div>

# Some other project
1. Short description
2. Link to IPython notebook