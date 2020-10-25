# MobileSoft 2021 - Native app vs their web app counterpart, which one consumes more? – Replication package


This repository contains the replication package and dataset of the paper with the title **Native app vs their web app counterpart, which one consumesmore?**.

This study has been designed, developed, and reported by the following investigators:

- Luciën Martijn (Vrije Universiteit Amsterdam)
- Stijn Meijerink (Vrije Universiteit Amsterdam)
- Dion David Haneveld (Vrije Universiteit Amsterdam)
- Daniël Hana (Vrije Universiteit Amsterdam)
- Terry Bommels (Vrije Universiteit Amsterdam)

For any information, interested researchers can contact us by sending an email to any of the investigators listed above.
The full dataset including raw data, mining scripts, and analysis scripts produced during the study are available below.

## How to cite this study
If this study is helping your research, consider to cite it is as follows, thanks!

```
@inproceedings{MobileSoft2021,
  title={{Native app vs their web app counterpart, which one consumes more?}},
  author={Luciën Martijn and Stijn Meijerink and Dion David Haneveld and Terry Bommels},
  booktitle = {Proceedings of the 8th IEEE/ACM International Conference on Mobile Software Engineering and Systems},
  year = {2021},
  pages = {to appear},
  numpages = {11}
}
```

### Overview of the replication package
---

This replication package is structured as follows:

```
    .
    |--- scripts/       		The scripts that have been used to collect the Android apps and to identify and extract IAMs calls from them.
    |
    |--- dataset/             	The full dataset used in the paper, including the raw files with IAMs calls, the questionnaire responses and the aggregated data by app category.
    |
    |--- libraries_classification/   	The results of the manual classification procedure performed for the Top 20 IAM using libraries.
    |
    |--- MobileSoft_2020.pdf             A copy of the paper in pdf format
```

Each of the folders listed above are described in details in the remaining of this readme.

### Dataset
---
```
dataset
    .
    |--- Top APKs Java Files   The raw java files found using IAMs extracted from apps mined from Google Play Store.  
    |--- OS Java Files         The raw java files found using IAMs extracted from Open Source apps in AndroidTimeMachine.
    |--- javaFilesSrcMl.xml    The java files in the folders above converted in a traversable xml format by means of Src.ML
    |--- questionnaire         The raw responses to our developer questionnaire.
    |--- Extracted_data.ods    Spreadsheet with collected data, aggregated by category and analysis.

``` 

### Scripts
---
Usage of the scripts is explained in [README](https://github.com/S2-group/mobilesoft-2020-iam-replication-package/blob/master/scripts/README.md) file inside the scripts folder.

### Libraries classification
---
```
libraries_classification
    .
    |--- classification.csv                      Results of the manual classification process of libraries. The csv includes the original purpose as classified indipendently by the two researchers as well as the final one after disagreements were solved.
```


## License

This software is licensed under the MIT License.
