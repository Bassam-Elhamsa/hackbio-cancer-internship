# **Unsupervised learning in cancer research**
## Author (Slack): @Bassam_Elhamsa
 

## **Introduction**:

Machine Learning empowers computers to learn from experience by performing tasks that can be evaluated through various algorithms and metrics \[1\] . A key area within this field is Unsupervised Learning, which deals with unlabeled data. Unlike supervised learning, where the data is labeled, unsupervised learning algorithms identify patterns and relationships within data without prior knowledge of its meaning \[2\]. Unsupervised learning basically operates on few common algorithms:

·        Clustering

·        Association

·        Anomaly detection

·        Latent variable

·        Dimensionality reduction

## **Case study: Clustering in cancer research:**

Clustering was used in a study\[3\] to identify distinct molecular subgroups of colorectal tumors based on genomic and transcriptomic data. The researchers applied unsupervised clustering to analyze promoter DNA methylation, mRNA expression, and miRNA expression profiles, which led to the discovery of specific molecular subtypes within the tumors and provided deeper insights into biological differences and similarities.

### **Key Findings:**

1. **Promoter DNA Methylation Clustering**:

   ·        Unsupervised clustering of the DNA methylation profiles of 236 colorectal tumors identified four distinct subgroups.

   ·        Two of these clusters were enriched for tumors with elevated rates of methylation and were classified as CIMP-high and CIMP-low, respectively. The remaining two non-CIMP clusters were primarily from tumors that were non-hypermutated and originated from different anatomical locations.

   ·        These clusters provided valuable insights into the epigenetic landscape of colorectal cancer.

2. **mRNA Expression Clustering**:

   ·        Unsupervised clustering of mRNA expression profiles revealed three distinct clusters.

   ·        One of the clusters significantly overlapped with CIMP-high tumors and was enriched for hypermutated tumors.

   ·        The remaining two clusters did not correspond to any specific group identified in the methylation data, suggesting differences in gene expression independent of methylation status.

3. **miRNA Expression Clustering**:

   ·        Clustering of miRNA expression profiles identified no clear distinctions between rectal cancers and non-hypermethylated colon cancers, implying that miRNA expression may not play a significant role in distinguishing tumors based on their anatomical origin.

4. **Integrative Clustering**:

   ·        An initial integrative analysis of MSI status, SCNAs, CIMP status, and gene expression profiles showed that colon and rectal cancers had similar patterns of genomic alteration when hypermutated tumors were excluded.

   ·        Based on this result, colon and rectal tumors were merged for further integrative analyses.

 

## **Conclusion**:

Unsupervised learning plays a pivotal role in extracting hidden patterns from unlabeled data, with clustering as a key technique. The colorectal cancer case study illustrates how unsupervised clustering can reveal distinct molecular subtypes, enhancing our understanding of cancer biology. Unsupervised learning thus holds transformative potential in precision medicine and data-driven research, by revealing critical biological differences and enabling more personalized medical approaches.

## **References**:

\[1\]    	N. A. Parasa, J. V. Namgiri, S. N. Mohanty, and J. K. Dash, “Introduction to Unsupervised Learning in Bioinformatics,” *Data Analytics in Bioinformatics: A Machine Learning Perspective*, pp. 35–49, Jan. 2021, doi: 10.1002/9781119785620.CH2.

\[2\]    	S. Naeem, A. Ali, S. Anam, and M. M. Ahmed, “An Unsupervised Machine Learning Algorithms: Comprehensive Review,” *International Journal of Computing and Digital Systems*, vol. 13, no. 1, pp. 911–921, 2023, doi: 10.12785/IJCDS/130172.

\[3\]    	D. M. Muzny *et al.*, “Comprehensive molecular characterization of human colon and rectal cancer,” *Nature 2012 487:7407*, vol. 487, no. 7407, pp. 330–337, Jul. 2012, doi: 10.1038/nature11252.

 

