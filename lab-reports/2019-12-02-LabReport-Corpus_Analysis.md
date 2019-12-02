# Lab Report: Corpus Analysis

#### Dipshika Chawla

## Process Description

For the corpus analysis lab we worked on the online R Studio platform. By definition, a corpus is a collection or set of things, and in our case we were working with a corpus of digitised books. We used the science fiction collection available in the Gutenberg Project database. This lab was a very useful extension to our Text as Data lab, and covered similar themes ranging from application of code in humanities, specifically English or broadly speaking, Linguistics. We used the lab 10 .Rmd file that Prof Cordell prepared for us beforehand. We prepared for the analyses by importing relevant libraries such as tidyverse, tidytext, and topicmodels. We built upon our skills and knowledge of R and explored new functions and rationale for analysis. The ability to think computationally was at the core of both our labs in R Studio. This lab introduced us to relatively sophisticated algorithms for more complex analyses. The corpus analysis involved careful layering of functions in order to perform accurate sentimental analysis and topic analysis on texts. We used our foundational knowledge of libraries, variables, observations, nested/unnested tokens, and the mutate function amongst others. One of our end results was an analysis of the ’angry’ sentiment in our chosen corpus. We discussed some of the top ‘angry’ sentiment books and visualised our data for improved comprehension and comparison of trends across different books - we used the slice function to prescribe the number of observations for analysis. The last part of this lab involved individual exploration wherein we analysed the corpus for a sentiment of our choosing. For this, I analysed the sentiment classified as ‘anticipation’ and interestingly discovered that there was an overlap in the books heavy on ‘anticipation’ and ‘sad’ sentiments. It’s almost funny because it’s as though the author maintains a sense of anticipation and hope, while the sadness curve continues to rise - and there is a high probability this is not true. Despite being a rather abstract observation derived from a small dataset, I think similar data explorations enable important findings.


## Observations

I enjoyed the corpus analysis for several reasons. It was different from our Text as Data lab as our data mining challenge was different in its nature. We had a more thematic, topical, and sentiment-based rationale, which is ‘fuzzier’ than simple extraction of words or count of unnested token that match a set criteria. This is less straight-forward as humanities data analysis has more nuances than numeric data analysis partly due to the nature of data, and due to the relatively recent application of code in humanities. Computer systems are popularly efficient at running instructions on voluminous databases. However, there is an added layer of consideration when humanities data needs unique standardisation, nesting (divisions), and well crafted rules and dictionaries for use. Objectively speaking, numeric data and rules are static. Results are black or white, 0 or 1. This is the desired (and arguably the only) output computer systems will generate, even for humanities data. So how are computers supposed to approach qualitative data, objective ideas, or open-ended information? There is a need to organise information, for example, classify language instances, such as ‘beer’ belonging to the happy or celebration sentiment dictionaries. Unlike the global number system, humanities data does not have a concrete hierarchy for words. Literary analysis is almost so-human that most people cannot even imagine a computer playing a role in the process. Hence, the aforementioned hierarchies and rules need to be defined by professionals to enable and best suit the analysis project.

In addition to the affordances offered by the application of computational thinking in humanities, the defining of ‘dictionaries, rules, and classifications’ is a tedious task. This is true for all data mining activities and can be very pronounced if there is considerable pre-analysis data cleaning and preparation. The various considerations that go into every building block of a functional system also hinder speed of the process. Even the best of algorithms are prey to misapplication of rules due to extreme outliers or the system’s incapability to identify unusual elements that are inherent to observations, such as the use of irony in textual data. Language is a creative space for many, which can heighten such challenges as authors often employ words, punctuation, and structure that are non-conforming enough to be misinterpreted by algorithms. I think it’s crucial for us to heavily experiment in digital humanities as it can open doors for new interdisciplinary research and optimisations such as improved serendipitous algorithms.


## Analysis

For this chapter, we read the _Fugitive Verses_ research by Cordell and Mullen. This was a very relevant example of corpus analysis as the algorithm allowed for identification of fugitive verses across 19th century American newspapers. This is a very compelling integration of technological advancements and humanities as it bridges the gap between 19th century corpuses that are not available as organised data for 21st century analysis. 

> We identify these clusters of reprinted texts algorithmically.


We jokingly discussed the frustration that surrounds infinite analyses on twitter data corpuses. It is awesome to derive insights and digital humanities techniques via Twitter data, however, working with 19th century newspapers poses a new set of ‘pre-processing’ challenges as I mentioned in the observations section. The data’s form - scanned copies of printed newspaper - itself can limit a researcher’s ability to use the wealth of existing algorithms that exist. Any analysis is followed by the OCR of the corpus as the algorithm can read this string data type. Eventually, the beauty of the process helps researchers identify trends beyond the reprinting count of fugitive verses. Personally, below are some of the findings I find most intriguing.

> Far more poems circulated anonymously, semi-anonymously, or uncertainly attributed. 

> As our examples thus far have shown, fugitive verses were defined as much by prose as by poetry. 




