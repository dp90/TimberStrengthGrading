# TimberStrengthGrading

Timber strength is predicted based on a nonlinear regression model, with indpendent variable material properties. The coefficients for these variables are determined in 4 ways:
1. From theory (physics of timber)
2. From direct regression
3. As the mean of a set of coefficients corresponding to a set of simulated datasets, in which the material defects are simulated.
4. As the mean of a set of coefficients corresponding to a set of simulated datasets, in which all material properties are simulated.

The IPython notebooks are used as the input for my bachelor's thesis and contain the following functionality:
1. DescriptiveStatistics.ipynb gives some descriptive statistics about the data and the correlations between the variables. It also fits a       number of probability density functions to each variable and finds which fits best.  
2. DsFromTheoreticalCs.ipynb uses option 1 (described above) to determine the variable coefficients, and predict the yield in each strength       class. It also gives some plots used in the report. 
3. DsFromDirectRegression.ipynb uses option 2 (described above) to determine the variable coefficients, and predict the yield in each             strength class. It also gives some plots used in the report. 
4. DsFromSimulation.ipynb uses option 3 and 4 (described above) to determine the variable coefficients, and predict the yield in each             strength class. 
5. PlotsPartialSim.ipynb plots the results from option 3 (described above). 
6. PlotsFullSim.ipynb plots the results from option 4 (described above). 
7. ModelWithoutKR.ipynb is a nonlinear regression model without the knot ratio as an independent variable, calculating the variable               coefficients directly from the data (so without simulations), to compare to the model that does incorporate the knot ratio. 

The paper is available upon request. Please contact me, if you are interested in the data. 

Python version 3.7.
