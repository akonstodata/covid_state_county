Analysis of county dynamics for COVID cases in Illinois
------------

INTRODUCTION
------------
The increase in COVID cases in a particular state will often be spread heterogenously in that state: some counties will be experiencing tremendous growth, whereas others will not.  It will be helpful, then, to track dynamics of virus spread at the county level.  Below, we present results from a statistical model fit of counties in Illinois.  We will be tracking which models fit cumulative growth the best: exponential, polynomial, or linear.  As virus growth spreads, the best model fit will veer away from exponential towards linear.  This is what we are looking for.

Contact: Anna Konstorum (konstorum.anna@gmail.com)

The Jupyter notebook for all updated results is found here [[1]](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/code/IL_COVID_Dynamics.ipynb)

CURRENT RESULTS
------------
Last update: 04/01/2020 9:00pm EST

Illinois
------------

![](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/results/IL_update.png)

The best model for Illinois is the quadratic model.  Prediction for number of total cases for 04/02 is 9641.

Illinois counties: coming soon!
------------

SOURCE DATA
------------
The COVID Tracking Project [[2]](https://covidtracking.com/).  


USAGE
------------
```
pipenv install
pipenv run jupyter notebook
```
