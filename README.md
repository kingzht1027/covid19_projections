# COVID-19 Projections Using Machine Learning

[covid19-projections.com](https://covid19-projections.com/), created by [Youyang Gu](https://youyanggu.com/)

*Warning: If you plan to clone this repository, please be aware that this repository takes approximately 4GB of space. This is because it contains all of our historical estimates and projections, not just the latest ones.*

**2020-11-19 Update:** We have uploaded our raw US infection estimates in the [`infection_estimates`](/infection_estimates) directory. For a slimmed down version that only has the latest infection estimates, visit [this repository](https://github.com/youyanggu/covid19-infection-estimates-latest).

**2020-10-06 Update:** Projections dated 2020-10-04 was our last model update. For more information, read [Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later). Follow [@youyanggu](https://twitter.com/youyanggu) on Twitter for continued COVID-19 insights.

We take a data-driven approach rooted in epidemiology to forecast infections and deaths for the COVID-19 / coronavirus epidemic in the US and around the world.

## Description of Folders

You can click on each folder to view the README for that folder.

* [`c19pro_score`](/c19pro_score) - Raw data for our [C19Pro Score](https://covid19-projections.com/maps/#c19pro-score)
* [`implied_ifr`](/implied_ifr) - Implied Infection Fatality Rate (IIFR) estimates
* [`infection_estimates`](/infection_estimates) - Infection estimates for the US **(New Nov 2020)**
* [`projections`](/projections) - Raw daily projections generated by our model
* [`r_values`](/r_values) - Reproduction number (R) estimates
* [`reich_forecasts`](/reich_forecasts) - Reich forecasts follow the format specified by the [Reich Lab](https://github.com/reichlab/covid19-forecast-hub)
* [`tests_target`](/tests_target) - Testing targets for every region based on our forecasts

The underlying SEIR simulator used to generate these projections is open source: https://github.com/youyanggu/yyg-seir-simulator. The simulator repository also includes the best learned values of [the various parameters](https://github.com/youyanggu/yyg-seir-simulator#parameters) for every region.

Our projections are featured on the [CDC website](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html).

We have also open-sourced our evaluation of our model and other CDC models: https://github.com/youyanggu/covid19-forecast-hub-evaluation.

## Other Repositories

- [Historical CDC Vaccination Data](https://github.com/youyanggu/covid19-cdc-vaccination-data)
- [Latest Infections Estimates](https://github.com/youyanggu/covid19-infection-estimates-latest)
- [COVID-19 Datasets](https://github.com/youyanggu/covid19-datasets)
- [SEIR Simulator](https://github.com/youyanggu/yyg-seir-simulator)
- [Model Evaluations](https://github.com/youyanggu/covid19-forecast-hub-evaluation)

Questions? Contact me on Twitter at [@youyanggu](https://twitter.com/youyanggu).

Site powered by [GitHub Pages](https://pages.github.com/).
