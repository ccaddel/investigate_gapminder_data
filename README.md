
# Investigating Gapminder Indicators

[The Gapminder Foundation](https://www.gapminder.org/) has collected a lot of data about how people live their lives in different countries, tracked over the years, on a number of different indicators. In this project, I'll take a look at four indicators I'm interested in understanding better and perform the Data Analysis Process (DAP) on them to uncover insights.

## About the Data

We'll be looking at each indicator across four decades by extracting data from 1980, 1990, 2000, and 2010/2011.

**Indicator 1**: Democracy Score (-10 is low, 10 is high)
 > This score is based on Polity IV, which is calculated by subtracting an autocracy score from a democracy score. It's a summary measure of a country's democratic and free nature. Anarchy, periods when normal government is suspended are coded as 0. There as been some interpolation for instances of foreign interruption, dissolved or merged countries, etc.

**Indicator 2**: GDP per Capita

 > This is in constant 2000 USD. The inflation but not the difference in cost of living between countries has been taken into account.

**Indicator 3**: Human Development Index - HDI (0 is low, 1 is high)

 > This is a summary measure of average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and having a decent standard of living. This is calculated by taking the geometric mean of normalized indices for each of the three dimensions (life expectancy index, Education index, GNI index).

**Indicator 4**: Urban Population (as a percentage of total population)

 ## Questions to investigate:

- Does there appear to be a relationship between more Democratic countries and GDP, HDI, or Urban Population? That said, do we need to first see if countries are becoming more democratic over time?

- Does there appear to be a relationship between urban population and HDI trends?

- Does there appear to be a relationship between GDP and HDI trends?

## Getting Started

### Workflow Setup

Create a Python environment in Jupyter Notebook tooled up with the following packages:

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- don't forget to add % matplotlib inline to see your graphs seamlessly

Upload the [datasets](https://www.gapminder.org/data/) for the four indicators.

### Conduct Analysis

- Clean and wrangle data
- Conduct Exploratory Data Analysis (EDA) to both validate and verify that all wrangling and cleansing is done, as well as understand the entirety of the data a bit better.
    - This will best prepare you to effectively pursue any sort of discovery that would bring light to the stated questions.
- Dive into seeking solutions to the stated questions, visualize and describe what you see.
- Make conclusions about what you've discovered, state the findings, and clarify any limitations in the data.
- Make recommendations based on the findings as well as any further analysis to conduct.

## How to Contribute

Find any typos? Have another resource you think should be included? Contributions are welcome.

First, fork this repository.

![](https://raw.githubusercontent.com/udacity/ud777-writing-readmes/master/images/fork-icon.png)

Next, clone this repository to your desktop to make changes.

`$ git clone {https://github.com/ccaddel/investigate_gapminder_data.git}`

`$ cd investigate_gapminder_data`

Once you've pushed changes to your local repository, you can issue a pull request by clicking on the green pull request icon.

![](https://raw.githubusercontent.com/udacity/ud777-writing-readmes/master/images/pull-request-icon.png)

Instead of cloning the repository to your desktop, you can also go to `README.md` in your fork on github.com, hit the Edit button (button with the pencil) to edit the file in your browser, then hit the `Propose file change` button, and finally make a pull request.
