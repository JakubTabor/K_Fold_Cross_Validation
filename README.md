# K_Fold_Cross_Validation
# I have "X" and "y" prepared so I can import "train_test_split" and get "train" and "test" set 
# Next I make "feature scaling" from "sklearn.preprocessing" I import "StandardScaler" 
# I prepare "X_train" using "fit_transform" method from my "scaler" """X_train = sc.fit_transform(X_train)""" and then my "X_test" """X_test = sc.transform(X_test)"""
# Then from "sklearn.svm" I import "SVC" model and set parameter "kernel" into "rbf"
