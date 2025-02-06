# Kaia-Quigg-Portfolio

# Socioeconomic Drivers of Ecological Footprint

*ipynb in 'notebooks'*

*csv in 'data'*


## TL;DR
This self-designed project utilizes advanced statistical analysis and visualization to answer questions regarding the 
relationships between Ecological Footprint and Biocapacity with respect to various socioeconomic indicators.
Visualizations were made primarily using the accompanying Tableau dashboard, as well as Python (matplotlib,seaborn) 


## Overview
This study explores the relationship between socio-economic indicators and ecological
sustainability using data collected by the Global Footprint Network. Analysis showed that
countries with higher Gross Domestic Product (GDP) per capita and Human Development Index (HDI) values exhibit 
greater ecological footprints. This suggests that heightened resource consumption is linked to economic development. 
Analysis across different regions indicates significant ecological deficits primarily attributable to carbon-intensive
activities, rather than mismanagement of natural resources. Predictive modeling demonstrates
that socio-economic factors are sound predictors of ecological footprint, underscoring the
importance of addressing carbon emissions and promoting sustainable practices to achieve
ecological balance. These insights contribute to the ongoing discussions on sustainable development
and policy-making that is aimed at mitigating global ecological impacts.


## Data
The data used for this project is from an existing dataset entitled Global Ecological Footprint
2023. It was found on Kaggle, and was sourced from The Global Footprint Network. The dataset
is updated yearly and is “Based on approximately 15,000 data points per country per year, the
accounts calculate the Footprints of more than 200 countries, territories, and regions from 1961
to the present.” The data are free and licensed under a Creative Commons
Attribution-ShareAlike 4.0 International License.
The dataset consists of n = 182 observations (countries) and p= 24 features. Twenty-one
variables are numerical, three are categorical.

https://www.kaggle.com/datasets/jainaru/global-ecological-footprint-2023/data


## Methods
- Data cleaning and preprocessing
- Statistical analysis
- Visualization


## Research Questions
1. How do socio-economic factors such as GDP per capita, HDI, and income group
correlate with a country's ecological footprint and biocapacity?
2. What are the regional variations in ecological footprint and biocapacity, and how do they
relate to resource consumption patterns?
- Analyze regional disparities in resource utilization based on land types.
3. Can predictive models be developed to forecast changes in ecological footprint based on
socio-economic trends?
- Explore the feasibility of predictive modeling to anticipate future shifts in
ecological sustainability.


## Results
Key findings:

Bringing together the results from all three research questions, it becomes evident that human activities, 
particularly those associated with economic development and carbon emissions, are the primary drivers of ecological 
footprints. Natural resource management practices, while important, do not appear to be the main
contributors to ecological deficits. Instead, the carbon footprint associated with human
infrastructure and industrial activities stands out as the predominant factor. This conclusion
underscores the need for strategies focused on reducing carbon emissions and promoting
sustainable development practices to address ecological deficits effectively.

The results from Research Question 1 demonstrate a clear relationship between socio-economic
factors and ecological impact. Higher Per Capita GDP and HDI are strongly associated with
higher Ecological Footprints, indicating that as countries develop economically and socially,
their environmental impact tends to increase. This highlights the importance of considering
sustainable development strategies to mitigate ecological impact while improving
socio-economic conditions.

The findings from Research Question 2 illustrate that the primary contributor to ecological
deficits may not be improper resource use, but rather human infrastructure and activities that
produce carbon emissions. Initially, the analysis of average Ecological Footprint and Biocapacity
across five land types showed that most regions were in ecological surplus or had only slight
deficits. This suggests that, for these land types, regions were generally managing their resources
adequately, and biocapacity was sufficient to meet the ecological demands. It was when the Carbon Footprint 
was included in the calculations, the number of regions in ecological deficit increased dramatically.
By separating the analysis of land types from the Carbon Footprint, this study clearly demonstrates that while
resource use is important, the dominant factor contributing to ecological deficits is the carbon
emissions resulting from human infrastructure and industrial activities. Therefore, mitigating
ecological deficits will require targeted efforts to reduce carbon emissions and transition to more
sustainable practices in human infrastructure and energy use.

The analysis from Research Question 3, using an OLS regression model to predict Ecological Footprint based on
socio-economic predictors, further supports these findings. The model's ability to explain a
substantial portion of the variance in ecological footprint suggests that economic and social
development, which are closely linked to carbon-intensive activities and infrastructure, play a
critical role in determining ecological impact.


