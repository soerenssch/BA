# Bachelor's Thesis

This repository serves as documentation for the code created and used for the thesis with the title:
"From Value Transactions to Transaction Value:
An Empirically based NFT Taxonomy and Identification of 
Best-Practice Configurations"

It includes code for data scraping, cleaning, sampling, and subsequent clustering.
As of Apr-25, the repository only entails the code, but not the fetched - and for the subsequent analysis - underlying data, due to storage constraints.

---

## Repo Structure

01 - Scraping
  1.  `010_collection_scraping` - Data scraping from multiple NFT marketplaces, resulting in four .db files.

02 - Cleaning
  1.  `020_data_cleaning` - Data cleaning and merging, resulting in a sampling population of over >5.5m collections.

03 - Sampling
  0.  `030_stratified_sampling` - Creation of a sampling frame, based on a randomized, non-proportional, and stratified sampling strategy.
  1.  `031_random_sample_1` - Drawing of the first random sample, which is used in the taxonomy's second iteration.
  2.  `031_random_sample_2` - Drawing of the second random sample, which is used in the taxonomy's third iteration.
  3.  `031_random_sample_3` - Drawing of the third random sample, which is used in the taxonomy's fourth iteration.
  4.  `031_random_sample_4` - Drawing of the fourth random sample, which is used in the taxonomy's fifth iteration.
  5.  `031_random_sample_5` - Drawing of the fifth random sample, which is used in the taxonomy's sixth iteration.
  6.  `031_random_sample_6` - Drawing of the sixth random sample, which is used in the taxonomy's seventh iteration.

040 - Clustering
  0.  `040_clustering` - Analysis of the decoded sampling frame, determination of the ideal number of clusters, clustering, and analysis of most important features/dimensions.
  1.  `041_Performance_Metrics` - Fetching of additional sales and performance data, statistical analysis via Kruskal‑Wallis H‑tests and boxplots.

---

## Miscellaneous 

The folder 'data' includes both the stratified samples used in each iteration of developing the taxonomy, as well as the results of the cluster analysis. 
Unfortunately, the underlying >5.5 million collections for the iterations are too large for GitHub. Should these be needed for further research or examination, feel free to reach out to me. 

---