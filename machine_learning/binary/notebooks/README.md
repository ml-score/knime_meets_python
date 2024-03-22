
a collection of Jupyter notebooks to create machine-learning models, store the parameters, columns and models with timestamps and collect them later to deploy them.

**kn_example_python_h2o_automl.ipynb** - basic H2O.ai AutoML project

**kn_example_python_h2o_automl_inspect_models.ipynb** - collect and inspect the models created

**kn_example_python_lightgbm_hyper_parameter_bayes_search_cv.ipynb** - Python LightGBM and **BayesSearchCV** to build model and deploy with KNIME Python nodes

**kn_example_python_lightgbm_hyper_parameter_optuna.ipynb** - Python LightGBM and **Optuna** hyper parameter tuning to build model and deploy with KNIME Python nodes

**kn_example_python_xgboost_hyper_parameter_optuna.ipynb** - Python XGBoost and **Optuna**h hyper parameter tuning to build model and deploy with KNIME Python nodes

--------

If you copy this to your local repository you might need the folders

/notebooks/

/model/

The data will be stored in the main directory. This is why under KNIME the standard directory directly under the workflow is /data/ and in the examples on the KNIME server I wanted to keep eneything together
