Simple linear regression using scikit learn
<h3>ERRATA </H3><br/>
Replace original code <br/>
X=data["Hours"]  <br/>
y=data["Scores"]  <br/>
By <br/>
X=data.iloc[:,0].values <br/>
y=data.iloc[:,1].values <br/>
