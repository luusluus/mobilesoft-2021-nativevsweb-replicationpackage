# MobileSoft 2021 - Native app vs their web app counterpart, which one consumes more? – Replication package


This repository contains the replication package and dataset of the paper with the title **Native app vs their web app counterpart, which one consumes more?**.

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
  author={Luciën Martijn and Stijn Meijerink and Dion David Haneveld Daniël Hana and Terry Bommels},
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
    mobilesoft-2021-nativevsweb-replicationpackage
    .
    |--- android-runner/                      Android-runner framework to execute experiments.
    |
    |--- dataset/                             The full dataset used in the paper.
    |
    |--- data-analysis/                       The R Markdown file for plotting and assessing the extracted data (see below).
    |
    |--- mobilesoft-2021-nativevsweb.pdf      A copy of the paper in pdf format
    
```

Each of the folders listed above are described in details in the remaining of this readme.

### android-runner
---
The source code of our fork of android-runner can be found here: https://github.com/bommels/android-runner.

### dataset
---
```
dataset
    .
    |--- Top APKs Java Files   The raw java files found using IAMs extracted from apps mined from Google Play Store.  
    |--- OS Java Files         The raw java files found using IAMs extracted from Open Source apps in AndroidTimeMachine.
    |--- javaFilesSrcMl.xml    The java files in the folders above converted in a traversable xml format by means of Src.ML
    |--- questionnaire         The raw responses to our developer questionnaire.

``` 

### data-analysis
---
```
data-analysis
    .
    |--- plots/                       Plot figures
    |
    |--- all_results.csv              Entire dataset
    |
    |--- data_pipeline.Rmd            R script for plotting and assesing the dataset
    |
    |--- data_pipeline.pdf            Output of R Markdown file in pdf format
```

## License

This software is licensed under the MIT License.
