# Machine Learning Project
## REPLICATING THE INTERPRETABLE KERNEL DIMENSION REDUCTION PROBLEM USING ITERATIVE SPECTRAL METHOD
### Contributors:
Hao Shu, Han Zhou, Gengyi Sun

### Abstract:
Data processing has always been one of the most popular approaches that data scientists used to
improve the performance of the models. Among all, the kernel method for support vector machine is
a powerful technique that can significantly reduce the dimensional complexity of the input features.
The standard approach that maps the dataset to a high dimensional space before the projection of
the dataset is strong at capturing the non-linear relationship among features but made the feature not
interpretive anymore. To solve the problem, an Interpretive Kernel Dimension Reduction method is
proposed. However, this method requires a non-convex manifold that is hard to solve. In the paper
recently published in NeurIPS 2019, C.Wu and his team have claimed a break though which extends
the theoretical guarantee of the Iterative Spectral Method(ISM), which was originally used solely
for Gaussian kernel in alternative clustering, to the entire family of kernels. Besides, they have
proved that this wide-ranged IKDR method can also be applied to all learning paradigms with an
outstanding performance compared with other commonly used IKDR methods such as Dimension
Growth and Steifel Manifold. To reproduce their work, we proposed an experimental approach to
their claimed baseline and result. We first concluded the three most important examine criteria from
their claimed contributions. Then we proceed with the experiment by examining each criterion we
concluded and checked if they met the claimed baseline. After a series of cautious experiments and
reproducing. We have confirmed the correctness of their work, hence validate the newly established
baseline. Not only verifying their work, but we have also discovered the trade-off between reducing
dimension and improving accuracy, hence built up a more insightful knowledge towards this area of
research.


Report available: [ here](https://github.com/JimShu716/NeurIPS-2019-Reproducibility-Challenge/blob/master/Report.pdf)

Original paper: [ here](https://arxiv.org/abs/1909.03093)
