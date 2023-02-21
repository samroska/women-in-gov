## Women in Government Project
University of Michigan - Applied Data Science
Milestone I

### Authors

- Rebecca Hailperin-Lausch
- Samantha Roska
- Samantha Russel

### Dependancies

| library | Verion use in development |
|---------|----------|
|matplotlib | 3.6.3 |
|numpy | 1.23.3 |
| pandas | 1.4.4 |
| plotly  | 5.13.0 |
| python | 3.10.6
| seaborn  | 0.12.2 |

 > There is output from 'pip3 list' from one of our machines located in file versions.txt. In a future iteration of this project we will use pyenv in order to have a smother development experience.

## Project Summary 

The 118th United States Congress boasts the highest percentage of women in history, with women making up 28% of the governing body (pew research). This fact has been cited to champion the US as a model of equality, however, how does this claim hold up when compared to other democratic countries? Using international government data, we will explore how women in government has changed in the past 20 years.

Our question: Do countries with democratic government have more women in their governing bodies?

## Data Sources

- [Women in National Parliments](http://archive.ipu.org/wmn-e/classif-arc.htm): This data has been pulled via a python scrip. You can find all the dataset within data/world_data with the naming convention 'wd_month_year'. The original script used to gather this data is within the data_cleaning.ipynb notebook. However, the line has been commented out in order to limit calls to the source website.

- [Democracy Index Score](https://www.eiu.com/n/campaigns/democracy-index-2021/): The democracy index score was how we categorized and defined the term 'democratic government'. This index is on a scale of 0-10. There are 4 main categories (Full democracy, Flawed Democracy, Hybrid Regimes, and Authoritarian Regimes) with ranges on the 1 - 10 scale.

- [ISO Code](https://raw.githubusercontent.com/plotly/datasets/master/2014_world_gdp_with_codes.csv):This was not a major data source and is not included in our report. This was used to get a complete list of ISO country code for the Choropleth graphs in the visualizations.ipynb


## Noteable Files

 - *Report-Who-runs-the-world.pdf* : This file is the report on our analysis of women in governemnt. This was the final PDF our group submitted for grading to Milestone I

 - *data_cleaning.ipynb* : All of the steps we performed to gather and format our source data is contained within this notebook. Pre-processing, dataframe manipulation, and output csv code is within this notebook.

 - *data_visualizations.ipynb*: After data cleaning and initial manipulation, we started exploring insights into the data via visualizations. Within this notebook you will find all the exploratory visualization we created. Not all visualizations within this notebook were included in the final report PDF.

## Project Limitations

Our data is from publicly available and widely cited data sources. Due to our data being at such a high, public level, we don’t have to worry about some common data ethical concerns such as PII exposure and informed consent. There may be an issue of missing perspectives: we chose to only include democratic countries to get as similar a comparison to the US as possible. However, by excluding other countries we may be missing valuable insights. Also, we are using gender here as a binary variable. However, gender is a spectrum and there may be non-binary people excluded when the data is coded this way. We also chose to focus on women as our area of interest. However, there are many other minorities that are also excluded from government leadership and are important to keep in mind. Expanding our research to other minorities would be a great next step to round out our project in the future.

## What's next?

- Finding additional data sources to help get a more clear picture of our initial question. 
- Having more detail on the government upper and lower house for countries.
- Using more advanced techniques like machine learning to help with analysis
- Building cloud skills like AWS SageMaker notebooks and S3 for .csv storage
- Code automation and integration with cloud provider. Github actions to auto publish notebook changes and analysis to run.
