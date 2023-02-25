<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/tubarao2.png" alt="" border="0">
</p>

# Shark Attack Study Around The Globe



This project aimed to find where are the places with most shark attacks in the world, and which one are more dangerous.

## Technology

The software  used in this project was:

* Python version  3.8.3

## Services Used

* Github


## Python Libraries

* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn



## Hipóteses

1- Did shark attacks raised in the last 40 years ?

2- In which countries we have more lethal attacks ?

3- Among the 5 countries with most lethal attacks, what are their letality ratio? How was it's progression in the last 40 years?



## Método

A DataFrame was created based on informations obtained in https://www.kaggle.com/search when seartching for Global Shark Attacks.
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/tabela_original.png" alt="" border="0">
</p>
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/colunasiniciais.png" alt="" border="0">
</p>
 

According to the hipoteses, a filter taking off some columns and unnecessary information was made. Also some fields in the DataFrame where we had no information, were filled.
The lines in "Fatal Y/N" column that were "NaN" were filled with information based on "Injury" column.
 <p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/tabeltafiltrada.png" alt="" border="0">
</p>
In order, some graphics were created to show the necessary information to get the answers I was looking for.
  


## Hipótese 1

### Did shark attacks raised in the last 40 years ?

Here we can see whether or not there has been an increase in attacks over the last 50 years.

<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/ataquesXano.png" alt="" border="0">
</p>
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/ataquesXpa%C3%ADs.png" alt="" border="0">
</p>

According to the graphic below, we can see that there has been a considerable increase in shark attacks (over 5 times from 1977 to 2017)
 
## Hipótese 2

### In which countries we have more lethal attacks ?

Here we can see which countries have the highest number of lethal attacks.

<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/letaisXpais.png" alt="" border="0">
</p>
 

As the graphic indicates, we can see that Australia,The United States, South Africa, Brazil and Reunion have more lethal attacks.
Interesting to note that even with much less attacks than the USA, Australia has more fatal attacks per year.

## Hipótese 3

### Among the 5 countries with most lethal attacks, what are their letality ratio? How was it's progression in the last 40 years?

Here we will see, individually, how the progression of lethal attacks rate  (# of lethal attacks divided by # of total attacks) has been in the last 40 years.

#### Australia
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/trendAUS.png" alt="" border="0">
</p>

#### The United States
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/trendUSA.png" alt="" border="0">
</p>

#### South Africa
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/trendSA.png" alt="" border="0">
</p>

#### Brazil
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/trendBR.png" alt="" border="0">
</p>

#### Reunion
<p align="center">
<img src="https://github.com/Thompaiva/PROJETOS/blob/main/screenshots/trendREU.png" alt="" border="0">
</p>


As we can see according to the graphics with trend lines, only in Brazil and South Africa we have an increase in the rate of lethal attacks, while in the USA, Australia and Reunion, it decreases.





## Features


 - Import from dataset
 - Data cleaning
 - Data manipulation
 - Data analysis
 - Creation of the linear regression model
 - Application of the model
 - Analysis of the result

## Links

  - Repository: https://github.com/Thompaiva/PROJETOS


## Versioning

1.0.0.0


## Authors

* **Thomas R. de C. Paiva**: @Thompaiva (https://github.com/Thompaiva/)