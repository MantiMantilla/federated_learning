# A friendly, non-technical introduction to differential privacy


[Link to article.](https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html)


A blog post series about differential privacy. Provides simple explanations and assumes no prior knowledge. The blog branches out into several articles.


## Intro.


Starting chapters.


### 1. Why differential privacy is awesome.


Differential privacy was introduced in 2006, after many failed attempts at methods to publish people's data while protecting their privacy.


As a premise, consider any data manipulation procedure (ML, stats, obfuscation, etc.). Differential privacy requires that the outcome of a process be basically the same when executed on incomplete data.


In this context, basically the same means that and outcome is equally likely from a complete dataset and an incomplete dataset. For this to be true, the process must introduce noise into the data before executing.


> Briefly mentioned in the blog, a dataset is said to be $k$-anonymous if every combination of identifying fields appears in at least $k$ records.


Differential privacy is a property of the process, not the data (unlike $k$-anonymity).





### 2. Differential privacy in (a bit) more detail.


Summary


## How to achieve differential privacy.


First branch.


### 3. Differential privacy in practice (easy version).


Summary

### 4. Almost differential privacy.


Summary
