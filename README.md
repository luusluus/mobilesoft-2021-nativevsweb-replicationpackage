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
    |--- android-runner/            Android-runner framework to execute experiments.
    |
    |--- dataset/                   The full dataset used in the paper.
    |
    |--- data_analysis/             The R scripts for plotting and assesing the extracted data (see below).
    |
    
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

### Data Analysis
---
```
data_analysis
    .
    |--- pwa_visualizations/          Plot figures
    |
    |--- all_cpu_cached_values.csv    values for CPU while using cache
    |
    |--- all_cpu_nocached_values.csv  values for CPU while not using caching
    |
    |--- all_data.csv                 entire dataset
    |
    |--- all_pwa_load_times.csv       values for PWA load times	
    |
    |--- main.R                       R script for plotting and assesing the dataset
    |
    |--- main_recent.R                slightly updated main.R	
```

## License

This software is licensed under the MIT License.
