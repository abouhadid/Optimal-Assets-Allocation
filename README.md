# Optimal-Assets-Allocation
#### Risk Management in Market Finance project

----------------------------------------------

Yassine ABOU HADID

Othmane AKHSAS

----------------------------------------------
In portfolio construction, avoiding the concentration of all assets in one investment is vital. Asset diversification serves as an effective strategy to mitigate both systematic risk and idiosyncratic shocks. By diversifying allocations, the entire portfolio becomes resilient to the fluctuations associated with individual stocks or specific securities classes.

Modern Portfolio Theory stands out as the ideal mathematical framework for constructing a portfolio that maximizes expected returns for a given risk level. Nevertheless, a recent trend challenges this conventional approach, introducing **graph theory** as an alternative for portfolio optimization. In the finance landscape, numerous quantitative firms leverage sophisticated mathematical tools to navigate the market. The pertinent question that arises, despite the allure of its sophistication, is whether graph theory proves effective in the realm of portfolio optimization.

In this project, we will test some graph theory concepts (Degeneracy Ordering, Maximal Clique Centrality..) in an attempt to optimize asset allocation in the EURO STOXX 50 index.

----------------------------------------------

**DATA:**
The EURO STOXX 50 is a stock market index of Eurozone stocks developed by STOXX, an index provider belonging to the Deutsche Börse Group. The index comprises 50 stocks from 11 eurozone countries. The EURO STOXX 50 represents blue-chip Eurozone companies considered leaders in their respective sectors.

We have chosen a 60/40 split, with 2014 to 2016 as the training horizon, and 2017 to 2018 as the testing horizon.

----------------------------------------------

**GRAPH CONSTRUCTION:**
We represent the nodes by the 50 composites. The correlation between the average return of two stocks is denoted by the weights. Only if the correlation exceeds the predefined threshold do we establish an undirected edge between two vertices.
