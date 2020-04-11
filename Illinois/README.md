Analysis of county dynamics for COVID cases in Illinois
------------

INTRODUCTION
------------
The increase in COVID cases in a particular state will often be spread heterogenously in that state: some counties will be experiencing tremendous growth, whereas others will not.  It will be helpful, then, to track dynamics of virus spread at the county level.  Below, we present results from a statistical model fit of counties in Illinois.  We will be tracking which models fit cumulative growth the best: exponential, polynomial, or linear.  As virus growth spreads, the best model fit will veer away from exponential towards linear.  This is what we are looking for.

We also plot crude Case Fatality Rate (CFR) for the state and counties.  

Contact: Anna Konstorum (konstorum.anna@gmail.com)

The Jupyter notebook for all updated results is found here [[1]](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/code/IL_COVID_Dynamics.ipynb)

CURRENT RESULTS
------------
Last update: 04/11/2020 9:00am EST

Illinois
------------

![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update.png)

![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update_p.png)



Illinois counties
------------

![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update_Cook.png)

![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update_Lake_McHenry.png)
![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update_county_p.png)

SOURCE DATA
------------
The COVID Tracking Project [[2]](https://covidtracking.com/).  
NY Times COVID Repository [[3]](https://github.com/nytimes/covid-19-data).


USAGE
------------
```
pipenv install
pipenv run jupyter notebook
```
