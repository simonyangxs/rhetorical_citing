# A simulation-based analysis of the impact of rhetorical citations in science

Honglin Bao (Harvard Business School hbao@hbs.edu) and Misha Teplitskiy (University of Michigan tepl@umich.edu)

This is the GitHub repository for our preprint "A simulation-based analysis of the impact of rhetorical citations in science". An earlier version of the paper is available here: https://arxiv.org/abs/2304.06190. Paper: https://www.nature.com/articles/s41467-023-44249-0

We have implemented 6 models:

*   The full model with heterogeneous readers (base model, model 1.1)
*   The null model with heterogeneous readers, threshold-fixed (model 1.2)
*   The null model with heterogeneous readers, citing-budget-fixed (model 1.3)
*   The full model with homogeneous readers (model 2.1)
*   The null model with homogeneous readers, threshold-fixed (model 2.2)
*   The null model with homogeneous readers, citing-budget-fixed (model 2.3)

In this repository, we provided a comprehensively detailed commentary on the base model (model 1.1). For the other five models which are derived from the base model, we highlight the distinctions that differentiate them from model 1.1.

我认为建模存在的问题：
1. 整个社群只有一个人？
2. 模型设置的问题：超过阈值裁剪的依据是什么？为什么为什么最大的fit(i,j)就是qi 的十分之一？
3. 参数选择也没有依据