# Feature selection (variable selection)
Feature selection is the process of selecting a subset of relevant features (variables, predictors) for use in model construction ([Wikipedia](https://en.wikipedia.org/wiki/Feature_selection))

### Filter methods
- **Gini index**
- **Mutual information** ([Wiki](https://en.wikipedia.org/wiki/Mutual_information))
  - [Conditional Likelihood Maximisation: A Unifying Framework forInformation Theoretic Feature Selection](http://jmlr.csail.mit.edu/papers/volume13/brown12a/brown12a.pdf) (2012) *Gavin Brown, Adam Pocock, Ming-Jie Zhao, Mikel Lujan*
  - [Feature Selection Based on Joint Mutual Information](https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.4424) (1999) *Howard Hua Yang, John Moody*
  - [Estimating mutual information](https://arxiv.org/pdf/cond-mat/0305641.pdf) (2003) *Alexander Kraskov, Harald Stoegbauer, Peter Grassberger*
- **mRMR** Minimum redundancy, maximal relevancy ([Link](http://home.penglab.com/proj/mRMR/), [Wiki](https://en.wikipedia.org/wiki/Minimum_redundancy_feature_selection))
  - [Feature selection based on mutual information: criteria of max-dependency, max-relevance, and min-redundancy](http://home.penglab.com/papersall/docpdf/2005_TPAMI_FeaSel.pdf) (2005) *Hanchuan Peng, Fuhui Long, Chris Ding*
- **Relief** ([Wiki](https://en.wikipedia.org/wiki/Relief_(feature_selection)))
  - [The Feature Selection Problem: Traditional Methods and a New Algorithm](https://www.aaai.org/Papers/AAAI/1992/AAAI92-020.pdf) (1992) *Kira Kenji, Larry Rendell*

### Wrapper methods
- **Boruta**. All-relevant feature selection ([CRAN](https://cran.r-project.org/web/packages/Boruta/), [PyPI](https://pypi.org/project/Boruta/))
  - [Boruta – A System for Feature Selection](https://www.mimuw.edu.pl/~ajank/papers/Kursa2010.pdf) (2010) *Miron B. Kursa,  Aleksander Jankowski,  Witold R. Rudnick*
- **MUVR** ([GitLab](https://gitlab.com/CarlBrunius/MUVR))
  - [Variable selection and validation in multivariate modelling](https://academic.oup.com/bioinformatics/article/35/6/972/5085367) (2018) *Lin Shi, Johan A Westerhuis, Johan Rosén, Rikard Landberg, Carl Brunius*

### Embedded methods
- **LASSO**
  - [Regression Shrinkage and Selection via the lasso](https://statweb.stanford.edu/~tibs/lasso/lasso.pdf) (1996) *Robert Tibshirani*
- **Elastic net**
  - [Regularization and variable selection via the elastic net](https://web.stanford.edu/~hastie/Papers/B67.2%20(2005)%20301-320%20Zou%20&%20Hastie.pdf) (2005) *Hui Zou, Trevor Hastie*
