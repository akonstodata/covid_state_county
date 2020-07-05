Analysis of county dynamics for COVID cases in Illinois
------------

INTRODUCTION
------------
The increase in COVID cases in a particular state will often be spread heterogeniously in that state: some counties will be experiencing tremendous growth, whereas others will not.  It will be helpful, then, to track dynamics of virus spread at the county level.  Below, we present results from a statistical model fit of counties in Maryland.  We will be tracking which models fit cumulative growth the best: exponential, quadratic, or linear.  As the cumulative growth in positive cases slows, the growth function will shift from exponential to quadratic (concave up), and eventually to quadratic (concave down) and linear.  A switch to either of the latter two function types will indicate a substantial shift to slower growth dynamics, which is what we are looking and working for.

We also plot crude Case Fatality Rate (CFR) for the state and counties.  

Contact: Anna Konstorum (konstorum.anna@gmail.com)

The Jupyter notebook for all updated results is found here [[1]](https://github.com/akonstodata/covid_state_county/blob/master/Illinois/code/IL_COVID_Dynamics.ipynb)

CURRENT RESULTS
------------
Last update: 07/04/2020 7:30am EST

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
