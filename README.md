# Natural Language Processing

[<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/adb2273bdbff7abeff8f16dbde9e88722827f356/svgs/brands/firefox.svg" style="height:30px;">][Software + ML]
[<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/adb2273bdbff7abeff8f16dbde9e88722827f356/svgs/brands/github.svg" style="height:30px;">][Code]

This is a set of code used to demonstrate basics of natural language
processing with some basic of machine learning.

## Notebooks

The notebooks contain code to demonstrate the concepts and how they are
applied in code and data.

### Regular Expressions

This shows how to use the `re` module in python as well as some examples of
the different Regular Expression (Regex) syntax.

**Main Concepts:**

*   Using Python's `re` module
*   Matching multiple cases with Regex's disjunction
*   Reusing the same pattern with Regex's quantifiers
*   Positioning the matches with Regex's anchors
*   Retrieving matches with Regex's capture groups
*   Looking before and after a match with Regex's lookahead and lookbehind

### Text Normalization

This notebook demonstrate the process of converting text into a standard form.
This is one of the first step in the pipelines for a natural language
processing project.

**Main Concepts:**

*   Exploring datasets using Regex
*   Splitting sentences and paragraphs to words
*   Transforming words into roots and base forms
*   Separating different sentences from a paragraph

### Part of Speech Tagging

This notebook contains code to show how words in the sentences are given their
sentence function, or their part of speech (POS).

**Main Concepts:**

*   Utilizing word order using N-Gram taggers
*   Training different machine learning algorithms to develop a POS tagger

### Word Classification

This notebook implements some basic pipelines for processing different words
for classification. Specifically, this contains a basic sentiment analysis
pipeline.

**Main Concepts:**

*   Balancing imbalance datasets
*   Creating word features for training models
*   Using a Naive Bayes algorithm for sentiment analysis
*   Interpreting results of a Naive Bayes algorithm

### Document Classification

This notebook extends the concepts in `Word Classification`. This creates a
document classification pipeline by determining what topic a paragraph is
discussing.

**Main Concepts:**

*   Creating paragraph features for training models such as counts and tf-idf
*   Using a Random Forest algorithm for document classification
*   Interpreting results of a Random Forest algorithm

### Information Extraction

This notebook contains topics related to Chunking and Named Entity Recognition
(NER). These are two concepts are often used for information extraction within
a text.

**Main Concepts:**

*   Working with sentence syntax tree formats
*   Creating syntax trees using rule based approaches
*   Training syntax tree models using different machine learning algorithms
*   Developing a NER model using Conditional Random Fields (CRF)

## Models

The `models` folder is used as the output of the trained models when running
the notebook. Specifically, the CRF models created by NLTK are stored here.

[Code]: https://github.com/baluyotraf/lecture-natural-language-processing (Code)
[Software + ML]: https://education.softwareplusml.baluyotraf.com/projects/natural-language-processing/ (Website)
