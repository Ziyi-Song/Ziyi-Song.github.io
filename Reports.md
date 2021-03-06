<h1>Some reports & Manuscripts</h1>

[Back to home page](README.md)

## Reading manuscripts on EM Convergence Rate

**[EM Convergence Rate](EM Convergence Rate.pdf)**\
Ziyi Song, Oct 2020, Ann Arbor, MI

This manuscript introduces Theorem 1 & Theorem 2 in paper [R. Dwivedi, N. Ho & K. Khamaru (2020)](https://arxiv.org/abs/1810.00828). The manuscript mainly shows that,
  - given an unbalanced Gaussian mixture model with two components, population EM Algo converges geometrically to the ture parameter wherever the initialization starts, and sample EM Algo converges geometrically to a ball with radius around the true parameter;
  - given a balanced Gaussian mixture model with two components, population EM still converges to the true parameter from arbitrary initialization, but the convergence gets exponentially slower when the iteration close to the true parameter.




## Reading reports on Dirichlet Process prior

**[DP Mixture inference derivations: an example](Ziyi DPM_infer_deri_example.pdf)**\
Ziyi Song, June 2020, Ann Arbor, MI

In this report, we discuss issues in Gaussian mixture model using data distributions derived as normal mixtures in the framework of Dirichlet processes. Besides dealing with these issues, as a natural by-product, we develop approaches to inference about the number of components and modes in a population distribution. This report follows Escobar and West (1995).


**[Dirichlet Process Report](Ziyi Dirichlet Process Report.pdf)**\
Ziyi Song, May 2020, Ann Arbor, MI
               
This report is comprised of what I think is most fundamental in Bayesian Nonparametric for novices. The report goes in a sequence of topics: Dirichlet Processes, Dirichlet Process Mixtures, Markov Chain Sampling for Dirichlet Process Mixture models, Hierarchical Dirichlet Processes, applications on autonomous multi-vehicle interaction sce- narios modeling.


## Research Summary on Variational Learning for Sparse Gaussian Process

**[Varitional Learning for Sparse Gaussian Process](Variaitonal Inference for Sparse GP.pdf)**\
Ziyi Song, May 2019, CUHK(SZ), China

This is a summary I wrote while I was conducting my undergraduate research supervised by [Prof. Feng Yin](https://sse.cuhk.edu.cn/en/faculty/yinfeng). Roughly speaking, the research project was to combine the variational method with grid spectral mixture (GSM) kernel developed from spectral mixture (SM) kernel and to alleviate the time complexity problem resulted from GSM kernel.

This summary was my lastest understading after I read the Variational Inference Chapter in Pattern Recognition and Machine Learning, and the 2013 paper Stochastic Variational Inference. 



## Course project reports

**[An adventure in Semi-supervised learning](stats 601 project report.pdf), [slides](Exploring_Semi_supervised_learning.pdf), STATS 601**\
Trong Dat Do & Ziyi Song, April 2020, Ann Arbor, MI

In this project, we study some semi-supervised learning algorithms and their connection to those that we learn on class. We focus on two questions:
  - How can we use unlabeled data to improve classification quality?
  - How can the limited labeled data help with clustering, especially when some labels not appeared in the labeled data but hidden in the unlabeled part, with a Semi Dirichlet Process Mixture model?


**[Adaptive Monte-Carlo Optimization](Biostat 615 project report.pdf), [slides](Adaptive Monte Carlo.pdf), BIOSTATS 615**\
Ziyi Song & Kexin Zhang, Dec 2019, Ann Arbor, MI

In this project, we utilize adaptive Monte Carlo method to improve KNN (K-nearest neighbors) and medoid computation implementation on time complexity savings with accuracy guaranteed. Adaptive Monte Carlo method was proposed in paper [V.Bagaria, G.M.Kamath & David N. Tse (2018)](https://arxiv.org/abs/1805.08321), combining Monte Carlo method and the celebrated Multi-armed Bandit (MAB) problem.


[Back to home page](README.md)
