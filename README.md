You have a set of binary categorical features and want to filter out those with low variance, Select a subset of features with a Bernoulli random variable variance above a given threshold, Just like with numerical features, one strategy for selecting highly informative categorical features and
filtering out less informative ones is to examine their variances. In binary features (i.e., Bernoulli
random variables), variance is calculated as where p is the proportion of observations of class 1. Therefore, by setting p, we can remove features
where the vast majority of observations are one class.
