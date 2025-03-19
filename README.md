# GPSR Decarbonisation Pathways

Genetic Programming Symbolic Regression for Modelling Decarbonisation Pathways in the Global Energy-Economy-Climate System


The ETSAP-TIAM Model is a community-developed process-based optimisation model of the global energy system, integrated with a climate and economy model that explicitly represents the energy technology processes within mining, transformation, refining, generation, transmissions of energy commodities to end-use energy service demands in industry, commercial, transport, residential, and agricultural sectors. It provides a tool to inform policy by examining the effects of policy changes on outcomes. However, the model is complex, large, and unwieldy, with a steep learning curve. In this repository, we develop a suite of regression models - in effect, making a model of the model. 

We provide three types of models:

* Genetic Programming Symbolic Regression, which outputs a readable, non-linear equation
* Random Forest
* Elastic Net, a sparse linear model.

The E-Net gives the most interpretable models. The RF gives the most accurate models. The GPSR hits a different point on the accuracy-interpretability curve, which may be very useful for some policy discussion.

The benefit of using a regression "model of the model" versus using the original ETSAP-TIAM model is both interpretability and instant response of the new model to parameter changes, allowing more direct feedback on possible policy changes. 

The repository contains data exploration, data cleaning, and regression modelling, as well as output and interpretation of results.


## Authors

* [James McDermott](https://github.com/jmmcd), University of Galway
* [Iain Morrow](https://www.linkedin.com/in/iain-morrow-36b5b9), Actionable Models
* [James Glynn](https://github.com/jamesglynn), Energy Systems Modelling Analytics


## Acknowledgements

This work was funded by Actionable Models via the European Digital Innovation Hub [FactoryXChange](https://www.factoryxchange.ie/), 2024-2025. FactoryXChange Reference Number: TICH252172. https://www.factoryxchange.ie/service-page/free-form-regression-modelling.


## Citation

To cite this research, this repository, or this code, please cite our GECCO 2025 poster:

```
@inproceedings{mcdermott2025gecco,
  title={Symbolic Regression for Modelling Decarbonisation Pathways in the Global Energy-Economy-Climate System},
  author={James McDermott and Iain Morrow and James Glynn and Panos Evangelos},
  booktitle={Proceedings of the Companion Conference on Genetic and Evolutionary Computation},
  year={2025}
}
```