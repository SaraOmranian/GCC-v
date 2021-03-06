# GCC-v

### Greedy Clustering Coefficient algorithm and its Variants

Identification of protein complexes from protein-protein interaction (PPI) networks is a key problem in PPI mining, and current solutions are parameter-dependent and suffer from small recall rates. Here we introduce GCC-v, a family of parameter-free algorithms to accurately predict protein complexes based on the clustering coefficient. GCC-v is easy to implement, scales with the network size, and provides insights in the hierarchical organization of PPIs. Through comparative analyses with gold standards and PPI networks from Escherichia coli, Saccharomyces cerevisiae, and Homo sapiens, we demonstrate that GCC-v outperforms twelve state-of-the-art approaches for identification of protein complexes by at least 25.6% with respect to twelve performance measures. We also show that GCC-v results in the exact recovery of ~ 35% of protein complexes in a pan-plant PPI network, and in 144 putative protein complexes in Arabidopsis thaliana, corroborated with knowledge on domain-domain interactions. We show that findings by GCC-v are not affected by network perturbations, which has direct implications on assessing the impact of the PPI network quality on the predicted protein complexes. 

The implementation of each version with an example is available in a separate Jupyter notebook.
