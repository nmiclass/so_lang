# Analysis of Most and Least Popular Languages of 2022

## Table of Contents

- [Project Motivation](#motivation)
- [File Descriptions](#files)
- [Usage](#usage)
- [Results](#results)
- [Licensing](#licensing)

## Project Motivation<a name="motivation"/>

This notebook answers three questions related to programming languages:
1. What programming languages are most popular?
2. What languages do people want to use next year?
3. How do languages relate to the age of the programmer?

Answering the first question will tell us the direct answer of what languages are currently popular (or at least at the time of the survey).  The second question gives us an indication of how the popularity of languages may change with time.  The third question also gives us some indication of how language popularity may change if we see that a language is mostly used by younger or older demographics. 

## Project Files<a name="files"/>

`stackoverflow_language_analysis.ipynb` is the only required file, and performs all the analysis.  The notebook will download and extract the 2022 Stack Overflow results to the directory the notebook is executed in.

## Usage <a name="usage"/>

To run the analysis notebook requires:
- Jupyter with Python 3
- Pandas
- Matplotlib

The notebook itself will download, extract, and import the 2022 Stack Overflow survey results, so these do not need to be obtained manually.  The survey data will only be downloaded and extracted if no files with the same name already exist, so it is important that survey data from other years (for example) not be present in the directory containing the notebook.

The cells in the notebook may be run sequentially in order to obtain the analysis results looking into the popularity of programming languages.

## Results<a name="results"/>

An overview of results is described [here](https://nmiclass.github.io/blog/).

## Licensing<a name="licensing"/>

The Stack Overflow Annual Developer Survey data is available at [https://insights.stackoverflow.com/survey](https://insights.stackoverflow.com/survey), and is the sole ownership of Stack Overflow.  The analysis notebook is freely available for usage or modification, and is released to the public domain.
