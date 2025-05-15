
# Probabilistic K-anonymity Extension (K<sup>N</sup><sub>P</sub>) for User Anonymity Evaluation on World-Scale Databases

Data and code used in the paper Probabilistic K-anonymity Extension (K<sup>N</sup><sub>P</sub>) for User Anonymity Evaluation on World-Scale Databases




## Execution

Create a virtual-env and install the requirements:

```bash
  python3 -m venv .venv
```

## Contents
Under the folder analysis, each notebook (.ipynb file) contains one of the analysis done in the paper:

* Under 4_attr/ folder, the code to analyze the data from the three platforms and the modifications on Meta. Each file indicates the corresponding platform. 
   
  * Files ending with _general compute K<sup>N</sup><sub>P</sub> across all the data in the corresponding platform.
  * Files ending with _by_country compute K<sup>N</sup><sub>P</sub> per country 

* The rest of the files compute the comparisons generaly and by country, across platform (comparative) and across different scenarios of attribute cardinality on Meta (metacomparative).

Under the folder data, the audiences data collected from the Advertising Platforms, and the K<sup>N</sup><sub>P</sub> values computed with the notebooks under analysis/4attr/.

Under the folder theory_part, the notebook that generates the synthetic example of Section 3, and computes K<sup>N</sup><sub>P</sub> for that scenario.


    