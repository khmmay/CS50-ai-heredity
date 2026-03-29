\# 🧬 Heredity (CS50 AI)



\## 📌 Overview

This project implements a probabilistic model to determine the likelihood that individuals in a family have a particular genetic trait.



Using principles of \*\*probability theory and inheritance\*\*, the program computes the probability distribution for each person having 0, 1, or 2 copies of a gene, as well as whether they exhibit a trait.



\---



\## 🧠 How It Works



The program models genetic inheritance using:



\- \*\*Bayesian probability\*\*

\- \*\*Joint probability distributions\*\*

\- \*\*Conditional probabilities\*\*



For each possible configuration of:

\- gene counts (0, 1, or 2)

\- trait presence (True or False)



the program:

1\. Computes the \*\*joint probability\*\*

2\. Updates cumulative probabilities

3\. Normalizes results so distributions sum to 1



\---



\## 🧬 Genetic Model



Each person can have:



\- \*\*0 copies of the gene\*\*

\- \*\*1 copy of the gene\*\*

\- \*\*2 copies of the gene\*\*



Trait probability depends on gene count:



| Gene Copies | Trait Probability |

|------------|------------------|

| 2          | High             |

| 1          | Medium           |

| 0          | Low              |



The model also accounts for:

\- \*\*Parental inheritance\*\*

\- \*\*Mutation probability\*\*



\---



\## ⚙️ Features



\- Computes gene probability distribution for each individual  

\- Computes trait probability distribution  

\- Handles inheritance from parents  

\- Accounts for mutation probability  

\- Works for arbitrary family trees  



\---



\## 📂 Project Structure



```

heredity/

│── heredity.py     # Main program

│── data/           # CSV files with family data

```



\---



\## ▶️ Usage



Run the program with a dataset:



```bash

python3 heredity.py data/family0.csv

```



\---



\## 🧪 Example Output



```

Harry:

&#x20; Gene:

&#x20;   2: 0.0092

&#x20;   1: 0.4557

&#x20;   0: 0.5351

&#x20; Trait:

&#x20;   True: 0.2665

&#x20;   False: 0.7335

```



\---



\## 🧩 Key Concepts



\- Probability distributions  

\- Bayesian inference  

\- Joint probability  

\- Conditional probability  

\- Genetic inheritance modeling  



\---



\## 🚀 Possible Improvements



\- Visualize family trees and probabilities  

\- Optimize computation for large datasets  

\- Extend to more complex genetic traits  

\- Add a graphical interface  



\---



\## 📚 Acknowledgements



This project is part of Harvard's \*\*CS50: Introduction to Artificial Intelligence with Python\*\*.



\---



\## 👨‍💻 Author



Karl Henrik May 

https://github.com/khmmay

