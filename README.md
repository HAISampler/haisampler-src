
# High Average-Utility Itemset Sampling under Length Constraints

Cite: "Diop, L. (2022). High Average-Utility Itemset Sampling Under Length Constraints. In: Gama, J., Li, T., Yu, Y., Chen, E., Zheng, Y., Teng, F. (eds) Advances in Knowledge Discovery and Data Mining. PAKDD 2022. Lecture Notes in Computer Science(), vol 13281. Springer, Cham. https://doi.org/10.1007/978-3-031-05936-0_11"

High Utility Itemset extraction algorithms are methods for discovering knowledge in a database where the items are weighted. Their usefulness has been widely demonstrated in many real world applications. The traditional algorithms return the set of all patterns with a utility above a minimum utility threshold which is difficult to fix, while top-k algorithms tend to lack of diversity in the produced patterns. We propose an algorithm named HAISAMPLER to sample itemsets where each itemset is drawn with a probability proportional to its average-utility in the database and under length constraints to avoid the long and rare itemsets with low weighted items. The originality of our method stems from the fact that it combines length constraints with qualitative and quantitative utilities. Experiments show that HAISAMPLER extracts thousands of high average-utility patterns in a few seconds from different databases.

![haisampler1](https://user-images.githubusercontent.com/91367129/139295862-1fda15b2-f825-445f-b761-d9ca94613e90.PNG)
![haisampler2](https://user-images.githubusercontent.com/91367129/139295749-dc294d8e-ed3d-4074-ab3d-b6c98eb6ee25.PNG)
