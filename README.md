# GDP_EDA

## NITI Aayog: Background
NITI Aayog (National Institution for Transforming India) is a policy think tank of the Government of India; it provides strategic inputs to the central and the state governments to achieve various development goals. In the past, NITI Aayog has played an important role in initiatives such as Digital India, Atal Innovation Mission and various agricultural reforms and have designed various policies in education, skill development, water management, healthcare, etc. 

NITI Aayog was established to replace the Planning Commission of India, which used to follow a top-down model for policy making, i.e., it typically designed policies at the central level (such as the 5-year plans). On the other hand, NITI Aayog designs policies specific to the different states or segments of the economy.

Finance Minister, Arun Jaitley, made the following observation on the necessity of creating NITI Aayog, "The 65-year-old Planning Commission had become a redundant organisation. It was relevant in a command economy structure, but not any longer. India is a diversified country and its states are in various phases of economic development along with their own strengths and weaknesses. In this context, a ‘one size fits all’ approach to economic planning is obsolete...".

## Project Brief:
The NITI Aayog will provide top-level recommendations to the Chief Ministers (CMs) of various states, which will help them prioritise areas of development for their respective states. Since different states are in different phases of development, the recommendations should be specific to the states.

The overall goal of this project is to help the CMs focus on areas that will foster economic development for their respective states. Since the most common measure of economic development is the GDP, you will analyse the GDP of the various states of India and suggest ways to improve it.

## Understanding GDP:
Gross domestic product (GDP) at current prices is the GDP at the market value of goods and services produced in a country during a year. In other words, GDP measures the 'monetary value of final goods and services produced by a country/state in a given period of time'.

GDP can be broadly divided into goods and services produced by three sectors: the primary sector (agriculture), the secondary sector (industry), and the tertiary sector (services).

It is also known as nominal GDP. More technically, (real) GDP takes into account the price change that may have occurred due to inflation. This means that the real GDP is nominal GDP adjusted for inflation. We will use the nominal GDP for this exercise. Also, we will consider the financial year 2015-16 as the base year, as most of the data required for this exercise is available for the aforementioned period.

## Per Capita GDP and Income:
Total GDP divided by the population gives the per capita GDP, which roughly measures the average value of goods and services produced per person. The per capita income is closely related to the per capita GDP (though they are not the same). In general, the per capita income increases when the per capita GDP increases, and vice-versa. For instance, in the financial year 2015-16, the per capita income of India was ₹93,293, whereas the per capita GDP of India was $1717, which roughly amounts to ₹1,11,605. 

India ranks 11th in the world in terms of total GDP; however, it lies at the 139th position in terms of per capita GDP.

## Data :
The data is sourced from https://data.gov.in/, an Open Government Data (OGD) platform of India. The data for GDP analysis of the Indian states is divided into two parts:

Data I-A: This dataset consists of the GSDP (Gross State Domestic Product) data for the states and union territories.

Data I-B: This dataset contains the distribution of GSDP among three sectors: the primary sector (agriculture), the secondary sector (industry) and the tertiary sector (services) along with taxes and subsidies. There is separate dataset for each of the states. One is expected to read the dataset for the available states and join these if needed.

Data II: This section will require the dropout rate dataset apart from the dataset that you used in Part-1 of the case study.
 
## Description:
There are two parts to this project. In the first part, we will analyse and compare the GDPs of various Indian states (both total and per capita). The GDP of a state is referred to as the GSDP (Gross State Domestic Product). Then, we will divide the states into four categories based on the GDP per capita, and for each of these four categories, we will analyse the sectors that contribute the most to the GDP (such as agriculture, real estate, manufacturing, etc.).

In the second part, we will analyse whether GDP per capita is related to dropout rates in schools and colleges.

Part-I:

We will categorise the states into four groups based on the GDP per capita (C1, C2, C3, C4, where C1 would have the highest per capita GDP and C4, the lowest). The quantile values are (0.20,0.5, 0.85, 1), i.e., the states lying between the 85th and the 100th percentile are in C1; those between the 50th and the 85th percentiles are in C2, and so on.
Note: Categorisation into four groups will simplify the subsequent analysis, as otherwise, comparing the data of all the states would become quite exhaustive.

Note-I: The nomenclature for this project is as follows: primary, secondary and tertiary are named 'sectors', while agriculture, manufacturing etc. are named 'sub-sectors'.

Note-II: If the top 3 sub-sectors contribute to, say, 79% of the GDP of some category, we can report "These top 3 sub-sectors contribute to approximately 80% of the GDP". This is to simplify the analysis and make the results consumable. (Remember, the report is to be presented to the CMs, and CMs have limited time; so, the analysis needs to be sharp and concise.)

Part-II: GDP and Education

Analyse if there is any correlation of GDP per capita with dropout rates in education (primary, upper primary and secondary) for the year 2014-2015 for each state.
