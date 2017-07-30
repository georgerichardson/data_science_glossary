Data Science Glossary
=====================

This is a glossary of terms found in data science. It's aim is to provide a the reader with a friendly description of concepts, techniques, and packages, as well as point them towards resources for further information.

## Topics

- [**Data Analysis**](data-analysis/data-analysis.md)

- [**Data Engineering**](data-eng/data-eng.md)

- [**Data Visualization**](data-viz/data-viz.md)

- [**Deep Learning**](deep-learning/deep-learning.md)

- [**Machine Learning**](ml/ml.md)

- [**Natural Language Processing**](nlp/nlp.md)

- [**Statistics**](stats/stats.md)


## Contribute

There are many aspects of data science. Help covering them is greatly appreciated! If you would like to add a new term or section, or think an existing description can be modified, the please submit a pull request, or file an issue with a suggestion or question.

### Contribution Guidelines

Each topic area listed above has its own page. Within the pages, there are sections for Concepts, Methods, Terms, and Tools. These are loose definitions but are roughly summarised as:

- Concept - a practical or conceptual object relating to the topic (e.g. unsupervised machine learning).
- Method - a specific method of implementation relating to a concept (e.g. k-means clustering).
- Term - a word or phrase that has a specific meaning in data science other than its common meaning (e.g. feature).
- Tool - typically a piece of software that can be used to implement data science techniques (e.g. scikit-learn).

This guide is written in Markdown, [which is very easy](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)! Items added to the glossary should be formatted as follows:

~~~markdown
#### Item Title
The description of the item should be a few sentences
long, perhaps including an example, and easy to understand
for a beginner. It should not try to explain the full theory
behind the item. Sources can be included and formatted as
follows. [[source title](source link)]
~~~

The result should be something like this:

---

#### Token  
An element of a chopped up body of text, which could be a word or a group of words to analyse. The task of turning a body of text into tokens is called "tokenisation". [[Spacy Tutorial]
(https://github.com/cytora/pycon-nlp-in-10-lines/blob/master/00_spacy_intro.ipynb)]

---

There are no hard rules to the glossary, so if you feel that an item could fit into a few different categories, then just use your best judgement to choose one. In some cases there can be a case for multiple entries.

#### Multiple Entries

Sometimes an item may fit into more than one section because it actually has different meanings or uses depending on the topic. For example, the tool, `TensorFlow` is a deep learning package that is directly related to Deep Learning, but also has applications in Natural Language Processing. In this case it would be acceptable to have two separate entries with domain-specific descriptions. If applicable, a link can be added to an entry, to guide the reader back to the "original entry".

#### Not sure?

Not sure if you have enough experience to contribute? Read this project's [impostor syndrome disclaimer](impostor-syndrome-disclaimer.md)!