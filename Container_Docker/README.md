Ce dossier contient tous les containers Docker.

Chaque dossier contient son dockerfile permettant la construction de l'image, ainsi que les packages associés permettant d'introduire toutes les bibliothèques nécessaires à la construction de l'image. 

## Pour les images Docker de l'époque de l'article:
| **Dossier / outil** | **Description** | **Version** |
| ------------------- | ----------------|------------- |
| **`Bowtie`**        | Contient les fichiers liés à l’alignement des lectures avec **Bowtie2** (scripts, index, paramètres).   |   **0.12.7**    |
| **`FeatureCounts_Docker`** | Contient les fichiers ou scripts liés à la quantification des lectures avec **featureCounts**.     |  **1.4.6-p3** |
| **`TrimGalore`**    | Contient les fichiers relatifs à **TrimGalore**, wrapper autour de Cutadapt (options, logs, éventuellement scripts).        | **0.6.6**|
| **`R_DESeq2`**      | Contient le script R et les ressources nécessaires à l’analyse **DESeq2** (normalisation, tests différentiels, MA-plots, etc.). | **R : 3.4.1** **DESeq2 : 1.16** |
| **`SRA_Toolkit`**   | Contient les éléments nécessaires à l’utilisation de **SRA Toolkit** (scripts de téléchargement, métadonnées, logs).            | **latest** |


## Pour les images Docker récentes:
| **Dossier / outil** | **Description** | **Version** |
| ------------------- | ----------------|------------- |
| **`Bowtie`**        | Contient les fichiers liés à l’alignement des lectures avec **Bowtie2** (scripts, index, paramètres).   |   **1.3.31**    |
| **`FeatureCounts`** | Contient les fichiers ou scripts liés à la quantification des lectures avec **featureCounts**.     |  **2.0.6** |
| **`TrimGalore`**    | Contient les fichiers relatifs à **TrimGalore**, wrapper autour de Cutadapt (options, logs, éventuellement scripts).        | **0.6.10**|
| **`R_Deseq2`**      | Contient le script R et les ressources nécessaires à l’analyse **DESeq2** (normalisation, tests différentiels, MA-plots, etc.). | **R : 4.4.1** **DESeq2 : 1.44.0** |
| **`R_Deseq2_PCA`**      | Contient le script R et les ressources nécessaires à la réalisation d'une ACP | **R : 4.4.1** **DESeq2 : 1.44.0** |
| **`SRA_Toolkit`**   | Contient les éléments nécessaires à l’utilisation de **SRA Toolkit** (scripts de téléchargement, métadonnées, logs).            | **latest** |
