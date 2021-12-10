### Bring Your Own Model (XGboost)
`xgboost_BYOM_register.ipynb` shows first how to train an Xgboost model in scikit-learn and then inject it into Amazon SageMaker's first party XGboost container for scoring and then how to register the model. This addresses the usecase where a customer has already trained their model outside of Amazon SageMaker, but wishes to host it for predictions within Amazon SageMaker.