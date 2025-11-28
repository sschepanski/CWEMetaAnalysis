# Cold Water Exposure and Mental Health in Adults: A Systematic Review and Meta-Analysis

## Introduction

Mental disorders such as depression and anxiety remain among the leading causes of disability worldwide and are frequently associated with substantial psychosocial and physical burden. Although established pharmacological and psychotherapeutic treatments are effective, both face important limitations — including adverse effects, limited accessibility, and long waiting times for care. This has led to growing interest in complementary, low-threshold interventions that are safe, feasible, and biologically plausible.

Cold-water exposure (CWE), encompassing practices such as ice bathing, winter swimming, and cold showers — has recently gained considerable scientific and public attention as a potential strategy to improve mental health and well-being. Originating in traditional hydrotherapy and later integrated into wellness culture and sports medicine, CWE is hypothesized to influence mental health through repeated activation and adaptation of stress-response systems. Proposed mechanisms include autonomic and neuroendocrine regulation, modulation of inflammatory processes, and behavioral reinforcement of self-efficacy and control. Together, these pathways may contribute to improved mood regulation and stress resilience.

Despite increasing popularity, the evidence base for CWE remains fragmented. Individual studies vary widely in design, intervention protocols, and outcome measures, and few have investigated clinical populations or long-term effects. A prior systematic review restricted to randomized controlled trials in healthy adults reported inconclusive results, underscoring the need for a broader synthesis.

The present project therefore provides a comprehensive systematic review and meta-analysis of CWE effects on mental health outcomes in adults. It integrates data from both randomized and non-randomized studies, covering depressive and anxiety symptoms, perceived stress, and general well-being, while also mapping associated physiological markers and safety aspects. By combining psychological outcomes with physiological correlates, this analysis aims to clarify the scope, magnitude, and mechanisms of CWE effects and to inform future clinical applications and research directions.

## Project Structure

- **`data/`**: Extracted study datasets and harmonized variables.
- **`scr/`**: R scripts for data preparation, effect-size computation, and meta-analytic modeling.
- **`graphs/`**: Visual outputs including PRISMA diagrams, forest plots, and risk-of-bias visualizations.

## Scripts

- **StudyQuality.ipynb**: Study Quality visualisation including RoB1, ROBINS-I, and ROBINS-E in an integrated plot.
- **Analysis.ipynb**: Main analytical notebook containing data import, model estimation (REML and robust models), and figure generation.

## Acknowledgements

This meta-analysis was conceptualized and conducted by Dr. Steven Ngandeu Schepanski as part of the Cold-Water Exposure and Mental Health project at Charité – Universitätsmedizin Berlin, in collaboration with interdisciplinary partners.

## Getting Started

1. **Clone this repository:**

   ```bash
   git clone https://github.com/sschepanski/CWEMetaAnalysis.git
   ```
2. **Set up your R environment:**
   Ensure that R is installed and configured. All required packages are integrated directly in the respective R scripts. When running a script, any missing packages will be prompted for installation.
3. **Run the provided R scripts:**
   Execute the R scripts found in the scr/ directory for data preprocessing, modeling, and assumption testing. Set your working directory to the root of the project to ensure smooth execution of the scripts.

## Contributions

This project analysis was conducted by **Dr. Steven Ngandeu Schepanski**, Florian Batta and several Co-Authors. It is part of the manuscript by Ngandeu Schepanski, Batta et al.

## License

This project is licensed under the MIT License.