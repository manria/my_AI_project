
# Automatizing part of literature search in systematic reviews

Building AI course project

## Summary

The AI would be trained to automatically exclude literature articles that are clearly outside of the scope of the research, and extract the abstracts, names and years of the more suitable articles in a clear format for the researchers to review.  


## Background

Literature search in academic systematic reviews is extremely time consuming when done manually. Good quality systematic reviews often take years. Some parts are necessary to do manually, as the researchers need to use their own judgement, but the first parts of the literature search are very easy to do and AI could be trained to do it automatically. As far as I know, all systematic reviews are done mostly manually, so the problem is very common in academia. From my own experience, the first stages of literature review are very boring, and rationally it does not make sense to pay academic professionals for manually filling excels.

## How is it used?

My solution would be used in academia, so it would mostly affect academic professionals and students doing systematic reviews by reducing their workloads. It would also help systematic research to be published faster, which would have implications to whoever the research topic concerns.


## Data sources and AI methods

Data is retrieved from databases that are commonly used in systematic reviews, for example, Embase, PubMed, CINAHL, etc. Data would be peer reviewed articles and other academic papers. Term Frequency Inverse Document Frequency (tf-idf) would be used to determine the topic of the article, and information could be extracted by regular expressions.

## Challenges

The solution does not automatize all stages of systematic reviews, so those stages would still have to be done manually.

## What next?

The more accurate judgements the AI is capable of making from research articles, the more tasks in research can be automatized. 


##  Acknowledgments

No sources used
