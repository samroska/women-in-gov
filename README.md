## Women in Government Project
University of Michigan - Applied Data Science

### Authors

- Rebecca Hailperin-Lausch
- Samantha Roska
- Samantha Russel

## Using this project

 - `git clone `
 - `git pull`
 - `git status`
 - `git add`
 - `git commit -m " "`
 - `git push`

## Project Summary 

The 118th United States Congress boasts the highest percentage of women in history, with women making up 28% of the governing body (pew research). This fact has been cited to champion the US as a model of equality, however, how does this claim hold up when compared to other democratic countries? Using congressional and international democratic government data, we will explore how women’s leadership in government has changed in the past 20 years in the US versus other democratic countries. Specifically, we will be examining gender from two different angles: how women as heads of state have progressed as well as how gender division percentages have changed in the United States as compared to the governing bodies of other democratic countries.  

## Data Sources

- [CAWP Data](https://cawpdata.rutgers.edu/women-elected-officials/position) :  from CAWP (Center for American Women and Politics) and contains women elected officials, from national down to local levels, in the United States since 1893.

- [Elected Women Officials](https://en.wikipedia.org/wiki/List_of_elected_and_appointed_female_heads_of_state_and_government) : contains information about female heads of state across the world from 1940 to now

- []():

## Project Scope

We will be looking into three aspects of gender equality in government in our analysis:
Distribution by country for percentage of women in government across all levels/chambers. Since all the countries are democratic and women’s rights to hold office vary, we will expect to see an increase in women in government over time. Countries that observe a decline would signal additional analysis of factors. Additionally, seeing how the US touts being a model for democratic governance, we want to see if this claim holds up when comparing US representation to other democratic countries.

Growth percentage of women representation over time in each country from 2001-2021. We expect to gain insight into if women have been gaining representation over time or if their representation has stalled/declined. This will give us insight into the direction women’s representation in government has been moving in recent years.

Comparison of women as heads of states between the 112 countries over time. Has the occurrence of a woman as a head of a democratic state become more or less prevalent in recent years? 


To explore these facets of equality, we will be calculating the following statistics for each:
Standard deviation would show how ’skewed’ results are
Mean/Median/Mode would show the ‘expected’ value for total number of women in government for a democratic nation
Numpy.variance, numpy.std, scipy.stats.skew
Visualizations to explore how this facet of empowerment has changed over time.


## Project Limitations

Our data is from publicly available and widely cited data sources. Due to our data being at such a high, public level, we don’t have to worry about some common data ethical concerns such as PII exposure and informed consent. There may be an issue of missing perspectives: we chose to only include democratic countries to get as similar a comparison to the US as possible. However, by excluding other countries we may be missing valuable insights. Also, we are using gender here as a binary variable. However, gender is a spectrum and there may be non-binary people excluded when the data is coded this way. We also chose to focus on women as our area of interest. However, there are many other minorities that are also excluded from government leadership and are important to keep in mind. Expanding our research to other minorities would be a great next step to round out our project in the future.
