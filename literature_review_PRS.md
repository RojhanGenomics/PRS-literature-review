# Literature Review: Polygenic Risk Scores (PRS) in Precision Medicine

**Author:** Mahdieh Rojhannezhad, Ph.D. in Genetics

---

## Abstract

Polygenic Risk Scores (PRS) represent a significant advancement in precision medicine, leveraging vast genomic datasets to quantify an individual's genetic predisposition to complex diseases. This review provides a concise overview of PRS, detailing their construction through the aggregation of small effect variants across the genome. We discuss the interpretation of these scores in the context of individual risk and their emerging clinical applications, such as disease prediction and risk stratification. Concurrently, critical limitations, including the influence of population stratification and the challenges posed by diverse ancestry, are examined. Furthermore, we address the ethical considerations surrounding PRS implementation and explore future directions, emphasizing the need for robust validation, improved methodologies, and integration with environmental factors.

**Keywords:** Polygenic Risk Score (PRS), Precision Medicine, Genomics, Risk Prediction, Genetic Predisposition, Population Stratification, Ancestry

---

## 1. Introduction to Polygenic Risk Scores (PRS)

The advent of large-scale genome-wide association studies (GWAS) has revolutionized our understanding of the genetic architecture of complex diseases. Unlike Mendelian disorders caused by single gene mutations, most common diseases such as cardiovascular disease, type 2 diabetes, and certain cancers, are **polygenic**, meaning they are influenced by the cumulative effect of many genetic variants, each with a small individual effect.

Polygenic Risk Scores (PRS) are a powerful tool designed to capture this polygenic influence. They quantify an individual's overall genetic susceptibility to a specific trait or disease by aggregating the effects of numerous common genetic variants (Single Nucleotide Polymorphisms, SNPs) across the genome. PRS are a key component in the rapidly evolving field of **precision medicine**, aiming to tailor medical treatment to individual characteristics, including their unique genetic makeup [1].

---

## 2. How PRS are Built and Interpreted

### 2.1 Construction Steps

The construction of a PRS typically involves several key steps:

1. **Variant Discovery (GWAS):** A discovery GWAS dataset is used to identify genetic variants associated with the trait of interest
2. **Variant Selection & Weighting:** Variants are selected based on statistical significance thresholds (e.g., p-value < 1×10⁻⁵) and weighted by effect size (log odds ratio or beta coefficient)
3. **PRS Calculation:** The final PRS for an individual is calculated by summing the weighted genotypes (0, 1, or 2 copies of the risk allele) for all included SNPs
4. **Clinical Interpretation:** Scores are compared to reference population distributions

### 2.2 Interpretation

Interpretation of a PRS involves comparing an individual's score to a reference population. Higher PRS values generally indicate a greater genetic predisposition to the disease. These scores are often presented as **percentiles**, allowing for risk stratification.

> **Example:** An individual in the top 10% of the PRS distribution for coronary artery disease might have a significantly elevated risk compared to someone in the bottom 10% [2].

It is crucial to understand that PRS represent **genetic predisposition, not deterministic outcomes**. They are best interpreted alongside other risk factors, such as lifestyle, environmental exposures, and clinical measurements.

---

## 3. Clinical Applications

The potential clinical applications of PRS are broad and rapidly expanding:

| Application | Description |
|-------------|-------------|
| **Early Disease Prediction** | Identifying high-risk individuals for targeted screening and preventive therapies |
| **Risk Stratification** | Enabling personalized management strategies across risk spectra |
| **Therapeutic Guidance** | Informing drug selection or response prediction (under investigation) |
| **Population Health Management** | Informing public health initiatives and resource allocation |

---

## 4. Limitations

Despite their promise, PRS face significant limitations:

| Limitation | Explanation |
|------------|-------------|
| **Ancestry Gap** | PRS from European GWAS show lower predictive power in non-European populations [4] |
| **Missing Heritability** | Current PRS explain only a small proportion of phenotypic variance [5] |
| **Environmental Factors** | Lifestyle and exposures are not yet fully integrated |
| **Misinterpretation Risk** | Both clinicians and patients may misunderstand PRS meaning |

---

## 5. Ethical and Ancestry-Related Challenges

### 5.1 Ancestry and Population Stratification

The "ancestry gap" in PRS performance is a major hurdle. Genetic variants associated with a disease in one population may not be the same or may have different effect sizes in another. This can lead to **health disparities** if PRS are applied without proper validation and adjustment for diverse ancestries [4, 6].

### 5.2 Other Ethical Concerns

- **Data Privacy and Security:** Genomic data is highly sensitive and requires robust protection
- **Potential for Discrimination:** Concerns about use in insurance or employment contexts
- **Misinterpretation and Over-reliance:** Risk of undue anxiety or false reassurance

---

## 6. Future Directions

The field of PRS is dynamic, with ongoing research focused on:

1. **Improving PRS Accuracy and Transferability** across diverse ancestries [6]
2. **Integrating Multi-omics Data** (transcriptomics, proteomics, metabolomics)
3. **Developing Dynamic PRS** that evolve over an individual's lifetime
4. **Establishing Clinical Implementation Frameworks** and validation standards [3]
5. **Advancements in Machine Learning** to capture non-linear interactions

---

## 7. Conclusion

The integration of PRS into precision medicine represents a paradigm shift, moving from a one-size-fits-all approach to a more personalized model of healthcare. Continued research, responsible development, and attention to ethical considerations will be key to realizing its full potential while mitigating risks.

---

## References

[1] Visscher, P. M., Wray, N. R., Zhang, P., Sklar, P., & Brown, M. A. (2017). Ten things you should know about polygenic risk scores. *Nature Reviews Genetics*, 18(10), 590-600.

[2] Khera, A. V., Chaffin, M., Aragam, K. G., Haas, M. E., Roselli, C., Choi, S. H., ... & Kathiresan, S. (2019). Polygenic risk score as a tool for coronary artery disease risk classification. *JAMA Cardiology*, 4(7), 613-620.

[3] Hindorff, L. A., Mehta, N., & Manolio, T. A. (2018). The future of genomic risk assessment and prediction. *Genetics in Medicine*, 20(11), 1311-1319.

[4] Martin, A. R., Real, A. J., Neale, B. M., & Wray, N. R. (2021). The utility of polygenic risk scores in diverse populations. *Nature Medicine*, 27(10), 1657-1662.

[5] Gibson, G. (2012). Classical explanations for so-called "missing heritability". *PLoS Genetics*, 8(5), e1002644.

[6] Popejoy, A. B., & Fullerton, S. M. (2019). Archiving genomic data: benefits and challenges. *The American Journal of Human Genetics*, 104(6), 1064-1071.