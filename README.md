# *Faecalibacterium prausnitzii*, depleted in the Parkinson’s disease microbiome, improves motor deficits in $\alpha$-synuclein overexpressing mice
Anastasiya Moiseyenko1,2, Giacomo Antonello2,3,4, Aubrey M. Schonhoff1,2, Joseph C. Boktor1,2, Kaelyn Long2,3,4, Blake Dirks7, Anastasiya D. Oguienko1, Alexander Viloria Winnett1,5, Patrick Simpson1, Dorsa Daeizadeh7, Rustem F. Ismagilov1,6, Rosa Krajmalnik-Brown7,8, Nicola Segata2,4, Levi D. Waldron2,3,4, and Sarkis K. Mazmanian1,2

Abstract: Gut microbiome composition is altered in Parkinson’s disease (PD), a neurodegenerative disorder characterized by motor dysfunction and frequently accompanied by gastrointestinal (GI) symptoms. Notably, microbial taxa with anti-inflammatory properties are consistently depleted in PD patients compared to controls. To explore whether specific gut bacteria may be disease-protective, we assembled a microbial consortium of 8 human-associated taxa that are reduced in individuals with PD across multiple cohorts and geographies (benCom-PD). Treatment of a-synuclein overexpressing (Thy1-ASO) mice, an animal model of PD, with this consortium improved motor and GI deficits. A single bacterial species from this consortium, Faecalibacterium prausnitzii, was sufficient to correct gut microbiome deviations in Thy1-ASO mice, induce anti-inflammatory immune responses, and promote protective colonic gene expression profiles. Accordingly, oral treatment with F. prausnitzii robustly ameliorated motor and GI symptoms, and reduced a-synuclein aggregates in the brain. These findings support the emerging hypothesis for functional contributions by the microbiome to PD and embolden development of potential probiotic therapies.

This repository contains the code and data used for the statistical analysis of motor behavior and gut physiology tests, and downstream protein assays from **Moiseyenko et al. (manuscript in preparation)**.  

A.D.Oguienko performed statistical analysis for motor and GI function assays. This research was funded in part by Aligning Science Across Parkinson’s (ASAP-020495 and ASAP-000375) through the Michael J. Fox Foundation for Parkinson’s Research (MJFF), as well as the Heritage Medical Research Institute to S.K.M. 


The repository includes:  
- Python notebooks implementing the analysis workflow   (.ipynb format)
- Input data tables (Microsoft Excel format)  
- Output `.csv` tables summarizing results from various statistical tests
- Output `.csv` tables containing bootstrapping results (each row contains values of the model parameters calculated for one out of 10_000 bootstrap samples; each file contains 10_000 rows corresponding to 10_000 bootstrap replicates)
- Western blot and dot blot images and values (jpg, Microsoft Excel format)
- Multiplex (Bioplex) readout (Microsoft Excel format)
- Voltatile fatty acids readout (Microsoft Excel format)

---

## Getting Started

### Requirements
No high-performance computing resources are required. All analyses can be run on a standard laptop or desktop computer.

### Installation
Clone this repository and set up the provided virtual environment:

```bash
git clone https://github.com/oguienko/amoiseyenko2025/
cd amoiseyenko2025
conda env create -f amoiseyenko2025.yml
conda activate amoiseyenko2025
