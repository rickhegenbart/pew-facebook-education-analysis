# Facebook Use by Educational Attainment

> **Master’s Psychology Research & Analytics Portfolio**
>
> This project was completed as part of my Master’s degree program in Psychology. It uses R to clean, recode, and visualize survey responses examining Facebook use across education levels.
>
> [View the complete Master’s Psychology Research & Analytics Portfolio](https://github.com/users/rickhegenbart/projects/1)

## Overview

This project preserves an R Markdown analysis based on the Pew Research Center January 2018 Core Trends Survey.

The analysis explores reported Facebook use across educational-attainment categories through data cleaning, categorical recoding, frequency tables, and bar-chart visualizations.

## Research Question

How did reported Facebook use vary across education levels among respondents in the Pew Research Center’s January 2018 Core Trends Survey?

## Analysis Approach

The R Markdown source file:

* Imports survey data from a CSV file.
* Recodes Facebook-use responses into descriptive categories.
* Recodes educational-attainment responses into meaningful labels.
* Creates frequency tables comparing Facebook use and education.
* Produces stacked and grouped bar charts with `ggplot2`.

## Tools

* R
* R Markdown
* `tidyverse`
* `ggplot2`
* `forcats`
* `pewdata`

## Repository Contents

```text
├── README.md
└── Pew.Rmd
```

## Data Availability

The original public-use survey dataset and codebook are not included in this repository.

The R Markdown file requires the corresponding Pew Research Center CSV data to reproduce the tables and visualizations. The data must be obtained separately and used in accordance with the source’s terms of use.

## Project Status

This repository documents the original analysis source code. A rendered HTML report can be added in the future if the original dataset is recovered.
