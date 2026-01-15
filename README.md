# 🧬 In Silico Viral Evolution Engine

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Bioinformatics](https://img.shields.io/badge/Field-Bioinformatics-green)
![Simulation](https://img.shields.io/badge/Type-Genetic%20Algorithm-red)

An advanced evolutionary simulation engine that models how viruses evolve to escape immune systems and develop resistance to vaccines.

## 🚀 Features

* **Biological Accuracy:** Simulates the Central Dogma (DNA -> RNA -> Protein).
* **MHC Binding Algorithm:** Calculates immune escape probabilities based on real amino acid properties.
* **Stability Control:** Implements a penalty system for mutations that destabilize protein folding.
* **💉 Vaccine Simulation:** Introduces a "Vaccine Event" at Generation 50 to observe bottleneck effects and variant emergence.
* **Phylogenetic Analysis:** Generates an evolutionary tree to track the lineage of the "Super Virus".

## 📊 Visualization

The simulation produces two key outputs:
1.  **Fitness Landscape:** Tracking population adaptation before and after vaccination.
2.  **Lineage Tree:** A visual graph of the winning virus's ancestry.

## 🛠️ How to Run

You can run this simulation directly in your browser via Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jKRlIoefN3NiEBN-8Ct0zeY3wV1OukML?usp=sharing)

## 🧠 Core Logic (Genetic Algorithm)

1.  **Population Initialization:** Random DNA generation.
2.  **Selection:** Viruses with the lowest binding scores (immune escape) survive.
3.  **Crossover & Mutation:** Survivors reproduce with point mutations.
4.  **Intervention:** Vaccination parameters change the fitness landscape mid-simulation.

---
*Developed by Dila - 2026*
