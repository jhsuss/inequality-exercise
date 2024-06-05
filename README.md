# WBS Beahvioural Science Summer School -- exercises based on the [GEOWEALTH](https://www.nature.com/articles/s41597-024-03059-9) project 

There are two sets of data and code:

* [Building a stacked ensemble](#stack)
* [Visualising wealth inequality](#viz)

Starter code is provided in R, but feel free to use whichever language/software you'd like with the data provided.

For stacking, the example code uses `stacks`, part of the `tidymodels` group of packages (https://stacks.tidymodels.org/). (We didn't use `stacks` when building the stacked ensemble for the paper -- you can find that code [here](https://github.com/jhsuss/wealth-inequality/blob/main/functions/fit_ensembles.R) -- as it is fairly straightforward to code-up directly, but `tidymodels` is a well-documented ecosystem to start with.) 

## <a id="stack"></a> Stacked ensemble

Starter code is available in the 'ex-stack' folder, and data for training the model via the Survey of Consumer Finances is available in the 'data' folder. The data is a subset of the full data used in the paper to reduce the time it takes to train some models.  

## <a id="viz"></a> 

The wealth inequality data is archived and downloadable at ICPSR: [https://doi.org/10.3886/E192306](https://doi.org/10.3886/E192306). You can find different measures of wealth inequality at different levels of aggregation. Additionally, a more    

There are numerous packages for visualising and mapping data in (or through) R. Code for different options are available in the 'ex-vis' folder.
