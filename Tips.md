# How to improve the result?

1. [Model hyperparameter tuning](https://en.wikipedia.org/wiki/Hyperparameter_optimization)
2. [Ensembling different models](https://en.wikipedia.org/wiki/Ensemble_learning)
3. Dataset balancing (you can also combine training and validation datasets)
4. [Feature engineering](https://en.wikipedia.org/wiki/Feature_engineering) including:
    * Clustering
    * Tasseled cap transformation
    * [Spectral indecies](https://www.indexdatabase.de)
    * Textural features (e.g. [SAGA GIS](https://saga-gis.sourceforge.io/saga_tool_doc/9.1.1/imagery_tools_11.html))
    * Reduce spatial resolution
5. Additional features:
   * Rada data from Sentinel 1
   * Normalized digital surface model (nDSM)
   * Panchromatic band (15 m)
   * Satellite scene from another date
6. Post-processing:
    * Modal filter
    * Sieve filter

It is recommended to use a machine learning framework, e.g. [tidymodels](https://www.tidymodels.org/), [mlr3](https://mlr3.mlr-org.com/) or [scikit-learn](https://scikit-learn.org/).
