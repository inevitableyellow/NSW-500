# Racing to Connect: How Remote Teams Retain Their Spark

This project is a part of the FA 2024 SI 500 course at The University of Michigan School of Information.

-- Project Status: Completed

### Partner

-   [Alice Inc.](https://alice.inc/)
-   Contact: [Paul Woods](https://www.linkedin.com/in/paulthedesigner/)

### Methods Used

-   Data Visualization
-   Ordinal Logistic Regression
-   Spearman's Rank Coefficient

### Technologies

-   R

## Project Description

The purpose of this report is to outline recommendations for the transformation of remote working modalities for Alice Incorporated. The insights extracted will be utilized by key stakeholders to execute changes to their company structure, to optimize creative collaboration within hybrid teams.

### Data Source

The Treasury. NSW Remote Working Survey. data.nsw.gov.au, <https://data.nsw.gov.au/data/dataset/nsw-remote-working-survey.>

> "A survey of 1,500 NSW workers from March and April 2021, commissioned to understand workers' experiences of and attitudes to remote and hybrid working. To be eligible, respondents had to be employed NSW residents with experience of remote working in their current job. After accounting for unemployed people and those whose jobs cannot be done remotely—for example, dentists, cashiers and cleaners—the sample represents around 59 per cent of NSW workers. Workers answered questions on:
>
> -   their attitudes to remote working
>
> -   the amount of time they spent working remotely
>
> -   their employers’ policies, practices, and attitudes
>
> -   how they spent their time when working remotely
>
> -   how barriers to remote working have changed
>
> -   the barriers they faced to hybrid working
>
> -   their expectations for future remote working"

This analysis primarily focused on the likert responses to questions covering remote work collaboration and remote work wellness. As an exploratory variable, remote work frequency was investigated to determine what degree it impacted each variable.

The *HH* and *likert* packages were used to visualize likert response data. Given more time, the visualizations would have been 100% stacked. There were also several plots generate by *ggplot2* for exploratory data analysis (EDA).

Ordinal logistic regression was ran twice: once for the relationship between collaboration and remote work frequency and once for the relationship between wellness and remote work frequency.

## Needs of this project

-   data exploration/descriptive statistics
-   data processing/cleaning
-   statistical modeling
-   writeup/reporting

## Deliverables

-   [Slide Deck](link)
-   [Report](link)

## Contributing Members

**Instructor: [Andrea Barbarin](https://www.linkedin.com/in/andreabarbarin/)**

#### Team Members:

| Name | Role |
|--------------------------------------------------|----------------------|
| [Paris Heard](https://www.linkedin.com/in/paris-heard/) | Data Scientist |
| [Michelle Lin](https://www.linkedin.com/in/michelle-lin-760306188/) | UX Researcher & Designer |
| [Mohammad Farhat](https://www.linkedin.com/in/mohammadfarhat14/) | UX Researcher |
| [Vanshika Gaur](https://www.linkedin.com/in/vanshikagaur12/) | Human-Computer Interaction |
