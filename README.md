# Impact of CoronaVac on Covid-19 outcomes of elderly adults in a large and socially unequal Brazilian city: A target trial emulation study
 
 
# Introduction
Here we provide the data and pipeline for: [Spatiotemporal pattern of COVID-19 spread in Brazil](https://science.sciencemag.org/content/early/2021/04/13/science.abh1558)

### Citation

> In submission 2021. DOI: XX.XXXX/XXXXX.XXXXXXX


# Abstract

Although CoronaVac was the only vaccine adopted for the elderly adults in the first months of the Gamma epidemic wave in Brazil, randomized clinical trials to evaluate its efficacy in the elderly population were limited. In this study, we used routinely collected surveillance and SARS-CoV-2 vaccination and testing data comprising the population of the fifth largest city of Brazil to evaluate the effectiveness of CoronaVac in adults 60+ years old against severe Covid-19-related outcomes. By using the target trial framework, we defined a retrospective cohort including vaccinated individuals who were matched with unvaccinated persons according to socioeconomic covariates. Using the cumulative incidence as the risk associated with each group, starting at day 14 since the receipt of the second dose, we found an 82.3% (95% CI 66.3 - 93.9) effectiveness against Covid-19-related death, 68.4% (95% CI 42.3 - 86.4) against ICU admission, and 55.8% (95% CI 42.7 - 68.3) against hospital admission. Our results show that, despite the critical delay in the delivery of vaccines by the Brazilian government and the limited evidence in efficacy trial estimates, CoronaVac contributed to preventing deaths and severe morbidity due to Covid-19 in elderly adults, the target population at the beginning of the vaccination campaign in Brazil.


__One Sentence Summary:__ Despite the critical delay in the implementation of an immunization program by the federal government, our study suggests that CoronaVac was pivotal in preventing an accentuating dramatic scenario in terms of lives lost to Covid-19.


![FIG1_JOIN_V3.png](folder/to/FIG1_JOIN_V3.png)

__Fig. 1 Epidemiology pattern of Covid-19 in Fortaleza, 2020-2022.__
*(a) Epidemiological curves of Covid-19 cases and deaths in Fortaleza, and major interventions implemented in the city, Jan 2020-July 2022. (b) Cases (gray) and (c) deaths (red) of Covid-19 and cumulative distribution of individuals vaccinated with 2 doses (we consider a single dose of the Janssen vaccine as equivalent to a two-dose regimen).* 



# Organization
We have organized this repo by method. Within each of the methods folders are separate `code`, `data`, and `README.md` files. For additional information see the `README.md` files for each method: 
- `1_spatiotemporal`  — the spatiotemporal clusters analysis.
- `2_geographical_center`  — the geographical center analysis. (Includes supplementary .gif files)
- `3_hoover` —  the Locational Hoover Index.
- `4_policy_response ` - the policy response indicators
- `5_social_distancing ` - the social distancing index
- `6_correlations` — the Pearson correlations
- `7_cluster` - the hierarchical cluster analysis
- `Figures` - All figures from the main document 


# Correspondence
For any issues with anonymization or major issues with the functionality of the script please [create an issue](https://github.com/mcastrolab/Brazil_Covid19_spatiotemporal/issues).


## License
The data collected and presented is licensed under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/), and the underlying code used to format, analyze and display that content is licensed under the [MIT license](http://opensource.org/licenses/mit-license.php). 


# Authors
- __Higor S Monteiro__: Department of Physics, Universidade Federal do Ceará | ![link--v2](https://user-images.githubusercontent.com/43140693/111211993-742aeb80-85a5-11eb-85b8-a1e2c5102d99.png) : [GitHub Profile](https://github.com/higorsmonteiro)
- __Antonio S Lima Neto__: Secretaria Municipal de Saúde de Fortaleza | ![link--v2](https://user-images.githubusercontent.com/43140693/111211993-742aeb80-85a5-11eb-85b8-a1e2c5102d99.png) : [Google Scholar](https://scholar.google.com.br/citations?user=ZTQLXYkAAAAJ&hl=pt-BR&oi=ao)
- __Rebecca Kahn__: Department of Epidemiology, Harvard T. H. Chan School of Public Health | ![link--v2](https://user-images.githubusercontent.com/43140693/111211993-742aeb80-85a5-11eb-85b8-a1e2c5102d99.png) : [Google Scholar](https://scholar.google.com.br/citations?user=ZTQLXYkAAAAJ&hl=pt-BR&oi=ao)
