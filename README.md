# Lazy-predict-one-line-check-accuracy-of-all-models-
here you can check how model fit 

# how to install 
**pip install lazypredict**

how to use :
 1. import lazypredict
 2. now by the problem check which type of problem then import models like supervised then     **from lazypredict.Supervised import LazyClassifier**.
 3. after that use it like   **clf = LazyClassifier(verbose=0,ignore_warnings=True, custom_metric=None)
models,predictions = clf.fit(X_train, X_test, y_train, y_test)**
 4. by print(models)  you can print all models accuracy 

  
 full example show in above file 
 
