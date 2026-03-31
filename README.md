# CARACTERISATION DES LIGNEES ET SOUS-LIGNEES DE LYMPHOCYTES B ET DE LEUR HÉTÉROGÉNÉITÉ PAR UNE ANALYSE PAN-CANCER DE DONNÉES SINGLE-CELL 

L'hétérogénéité des TIBs (Tumor-Inflitrating B cells) est étudiée grâce à une analyse pan-cancer de données single-cell.

### DATA
Les datas sont issues de l'étude de Yang et al et sont disponibles sur GEO sous le code GSE233236.

Le dataset comprend : 
- 42,099 cellules
- 18,315 genes
- 8 types de cancer

## Scripts

### 1. Clustering
Permet de réaliser : 
- Le preprocessing et le quality control
- Normalisation
- HVG
- PCA, UMAP
- Clustering non-supervisé et annotation

### 2. ROGUE

Ce script contient le code pour retrouver les résolutions à utiliser pour chaque clustering

### 3. top50_markers_par_cluster.xlsx
Fichier à télécharger pour obtenir un tableau excel contenant les 50 gènes définissant nos sous-clusters.

## Librairies et versions  

R version : 4.5.0

Packages principaux : 
- Seurat (v5.4.0)
- dplyr
- ggplot2
- patchwork
- tidyr
- ggpubr
- umap
- Matrix
- cowplot
- magrittr

