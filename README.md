## Example of a simple Excel-based Statistical Catch at Age Analysis

These Excel example of a simple Statistical Catch at Age Analysis is designed to walk through the structure and components of the SCA. It is designed to replicate the way, we might build an SCA from:

Sheet 'LH'
- incorporating life history/population parameters from other studies
- building vectors of age, length, weight, fecundity, survivorship, and vulnerability at age
- Check out https://zsiders.shinyapps.io/Welcome_Module/ Lab 5 on Yield-per-recruit if you need a refresher on these parameters.

Sheet 'Data'
- incoroporating the catch at age data
- visualizing the catch at age data

Sheet 'Mortality'
- Establishing some of our key parameters
- Deriving a few of the initial population and recruitment parameters
- Building our estimates of fishing mortality at time
- Building our estimates of fishing mortality at age and time
- Building our estimates of total mortality at age and time

Sheet 'Abundance'
- Forward projecting the numbers at age and time matrix
- Calculating the reproductive output over time
- Calculating the recruitment over time

Sheet 'CC Likelihood'
- Using the Baranov catch equation to estimate the predicted catch
- Building a lognormal likelihood for the observed and predicted catch deviations

Sheet 'F Likelihood'
- Building a normal likelihood to constrain our deviations of fishing mortality from the average F

Sheet 'CPUE Likelihood'
- Estimating the predicted CPUE
- Building a lognormal likelihood for the observed and predicted CPUE deviations

Sheet 'Full'
- The full model build from all the above components
- A few little additions to transform parameters for easier fitting and derive MSY reference points

Sheet 'CAA simulation'
- This sheet demonstrates a simulation engine that was used to generate the observed catch at age given the life history parameters and some parameters on fishing mortality and recruitment. 
- Modify the parameters of *scale*, *xpos*, and *sigmaF* to adjust the number of sine waves in the F time series, the x-axis starting position for the F time series, and the noise in the F time series.  



