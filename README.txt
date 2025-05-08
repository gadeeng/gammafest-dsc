This notebook is a notebook for the Data Science Competition held by IPB University, 2025.

Problem Statement:
The current paper recommendation system is not effective enough in providing relevant literature suggestions for the Holy Knights. The Elbaf Library needs a system that can help manage and present references that are in accordance with research needs. In addition, the relationship between papers is still difficult to map accurately, causing relevant references to often be missed.

The Holy Knights in this competition are asked to build a machine learning model that can overcome these challenges. This model must be able to predict the citation relationship between papers. The main problem faced is how to help the Elbaf Library in building an optimal paper reference recommendation system.

To evaluate the developed model, the MCC (Matthews Correlation Coefficient) evaluation metric will be used.


This dataset consists of pairs of scientific documents, each with metadata such as title, abstract, and year of publication. Each row of data represents the probability that the first document (paper) cites the second document (referenced_paper).

The task of the participants is to build a machine learning model to predict the value of is_referenced, i.e. whether the citation relationship actually occurs, based on the available information.
