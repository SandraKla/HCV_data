# HCV data

This dataset includes laboratory and demographic data (e.g., age) from blood donors and Hepatitis C patients. It is designed for classification and clustering tasks, focusing on distinguishing between blood donors and Hepatitis C cases.

Key Details:

    Type: Multivariate
    Domain: Health and Medicine
    Instances: 615 (representing patients)
    Features: 12

Variables:

    Demographics:
        ID, Category, Age, Sex
    Lab Values:
        ALB albumin, g/L
        ALP alkaline phosphatase
        ALT alanine aminotransferase, U/L
        AST aspartate aminotransferase, U/L
        BIL bilirubin, μmol/l
        CHE choline esterase, kU/L
        CREA creatinine, μmol/L
        GGT gamma-glutamyl transferase, U/L
        PROT total protein, mg/L

This dataset was featured in the study "Using machine learning techniques to generate laboratory diagnostic pathways—a case study" (Hoffmann et al., 2018, Journal of Laboratory and Precision Medicine).

The repository contains two datasets: the file *hcvdat0.csv* from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/571/hcv+data) and an adapted version for *reflimR* data, provided by the R package [*reflimR*](https://cran.r-project.org/web/packages/reflimR/).

To use the dataset within the *reflimR* package in R, you can load it as follows:

```R
# Load the reflimR package
library(reflimR)

# Access the dataset
livertests

# View the first few rows
head(livertests)
```
