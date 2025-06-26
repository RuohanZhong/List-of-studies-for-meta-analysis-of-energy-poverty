# Energy Poverty Meta-Analysis: Comprehensive Literature Database

## 📌 Overview
This repository contains a systematically organized collection of academic literature and analysis tables for studying energy poverty, focusing on two key dimensions:
1. **Incidence** of energy poverty
2. **Consequences** of energy poverty

## 📂 Repository Structure

### Bibliographic Data (BibTeX Format)
| File | Content Description |
|------|---------------------|
| `bib/incidence.bib` | Contains 150 studies on measurement methodologies, incidence rates, and spatial distribution of energy poverty |
| `bib/consequence.bib` | Contains 119 studies on social, economic, environmental, and comprehensive consequences of energy poverty |

### Analysis Tables (LaTeX Format)
| File | Content Description |
|------|---------------------|
| `table/incidence_table.tex` | Comparative table analyzing the incidences of energy poverty |
| `table/consequence_table.tex` | Synthesis table categorizing consequences by research time, country, and key findings |

## 🔧 Usage Guide

### For Literature Review
1. **Citation Management**:
   ```latex
   \bibliography{bib/incidence,bib/consequence}


graph LR
    A[incidence.bib] --> B[incidence_table.tex]
    C[consequence.bib] --> D[consequence_table.tex]
          
