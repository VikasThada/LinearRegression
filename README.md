Simple linear regression using scikit learn
#ERRATA
Replace original code
X=data["Hours"]
y=data["Scores"]
By
X=data.iloc[:,0].values
y=data.iloc[:,1].values
