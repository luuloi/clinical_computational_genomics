# Clinical Computational Genomics
### Location: Lầu 2, 201 Nguyễn Chí Thanh, Phường Chợ Lớn, TPHCM (Bệnh viện Đại học Y Dược CS2)
### Time: Thứ Hai hàng tuần từ 17:15 đến 19:15h
####
<p align="justify">The Clinical Computational Genomics course, as outlined in this repository, provides a comprehensive introduction to the algorithmic and statistical methods used to analyze large-scale genomic data with a focus on medical applications (Infectious Diseases and Human Genetic Diseases). The curriculum covers foundational bioinformatics topics such as sequence alignment Clustal, BWA, Bowtie (including Smith-Waterman and Needleman-Wunsch algorithms), BLAST and BLAT for gene prediction, gene annotation, and phylogenetic analysis. Additionally, the course delves into modern clinical workflows, including high-throughput sequencing data processing (FASTQC, Trimmomatic, Trimgalore...), variant calling (BCFTools and GATK), and the interpretation of genetic data for disease diagnosis and precision medicine. By combining theoretical lectures with practical computational exercises, the course prepares students to translate complex biological sequences into actionable clinical insights.</p>

####
## Part I: Background Preparation
### Lecture 1: Introduction to Next Generation Sequencing (NGS) and Long Read Sequencing in Clinical Genomics [Loi] - 16/03/2026, onsite
- [PDF](Lecture_01/Introduction_to_NGS_Loi_2026March16.pdf)
- Databases: [NCBI](https://www.ncbi.nlm.nih.gov/), [ENCODE](https://www.gencodegenes.org/), [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) and [UCSC Genome Browser](https://genome.ucsc.edu/)
### Lecture 2: Introduction to Linux Operation System, Google Drive & Colab, Github and Linux Command Lines [Phuc, Hung, Loi] - 24/03/2026, onsite
- [Linux commandline cheatsheet](https://linux-commands.labex.io/)
- [PDF](Lecture_02/Lecture_02_Introduction_to_Linux_OS_GG_Colab_Command_lines.pdf)
- Lab GGColab : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18pCXU8om8vvYoC10Cwb7x4ml0ihnknXb?usp=sharing)
- Homework GGColab : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tYnG5H8EH90x59W-wqsqHNGbrH6HpIkE?usp=sharing)
### Lecture 3: Introduction to Programming Language R & Data Visualization with GGPlot [Dan, Loi] - 30/03/2026, online
- [R cheatsheet](https://iqss.github.io/dss-workshops/R/Rintro/base-r-cheat-sheet.pdf)
- [GGplot cheatsheet](https://rstudio.github.io/cheatsheets/html/data-visualization.html)
- Short introduction to R: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1t3DF5xZgpvEzpBWAnyT69fv5Pa6xFKhL#scrollTo=hmapfpuEl3lr)
- Data visualization with ggplot2: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Se87oXxvsA95oIiK2_sl-X86sVlRzYnz?usp=sharing)
- [YouTube](https://youtu.be/q5Slw7uc1zA)
- [Data](Lecture_03/Osteo_data.csv)
##
## Part II: Bioinformatic Analysis for Whole Genome Sequencing (WGS) of infection pathogens (Bacteria and Fungi)
### Lecture 4: Detecting and Characterizing infection pathogens using Whole Genome Sequencing (WGS) in Clinical Setting [Tan, Phuc] - 06/4/2026, online
- [PDF](Lecture_04/Detecting_and_Characterizing_Infectious_Pathogens_Using_Whole-Genome_Sequencing_in_Clinical_Settings.pptx)
- Lab GGColab:  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ko8Yn4Ti9CPrOZ6dGUF7iEb_aMNtLFJl?usp=sharing)
- Homework GGColab
- [Data](https://drive.google.com/drive/folders/1BeWwpzRWNL1W1nrKlMLBkeHj_ErDyLCh?usp=sharing)
### Lecture 5: Bacterial WGS Essentials — MLST Typing and Antimicrobial Resistance (AMR) Gene Profiling [Tan, Phuc] - 13/4/2026, online
- [PDF](./Lecture_05/Bacterial_WGS_Essentials_MLST_Typing_and_Antimicrobial_Resistance_%28AMR%29_Gene_Profiling.pdf)
- Lab GGColab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FgcF6vIb82E8Ih9QAn9EqPIT7S5EqeIx#scrollTo=FQJfePnInkfX)
- Homework GGColab
### Lecture 6: Fungal WGS Essentials — Targeted Resistance Markers from Whole-Genome Data [Tan, Phuc] - 20/4/2026, onsite
- [PDF](./Lecture_06/Fungal_WGS_Essentials_Targeted_Resistance_Marker_from_Whole_Genome_Data.pdf)
- Lab GGColab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1x28QRHKYykykZofCicTxEUI3TS3j_LTA?usp=sharing)
- [Data](https://drive.google.com/drive/folders/1bm9spPIISfKSC7SZTSPJs6QDtpxefpsm?usp=sharing)
## Part III: Bioinformatic Analysis for Human Microbiome
### Lecture 7: Introduction to Microbiome [Phuc] - 27/4/2026, onsite
- [PDF](Lecture_07/Lecture_07_Introduction_to_Microbiome.pdf)
- Lab GGColab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AswkD19F2vakpRdEysTafH--2y_oWpJA)
- Homework GGColab
### Lecture 8: Sequencing strategies for Microbiome Analysis: Amplicon Sequencing and Shotgun Metagenomic [Khai, Hung, Phuc] - 04/5/2026, onsite
- PDF
- Lab GGColab: Amplicon Sequencing and Shotgun Metagenomic pipelines
- Homework GGColab
### Lecture 9: Clinical Application of Microbiome Analysis [Khai, Hung, Phuc] - 11/5/2026, onsite
- PDF
- Lab GGColab: Applying Amplicon Sequencing for Diagnosis
- Homework GGColab
##
## Part IV: Bioinformatic Analysis for Human Genomics
### Lecture 10: Introduction to Targeted Sequencing for Germline Inherited Disease Detection [Giau, Hung] - 18/5/2026, onsite
- PDF
- Lab GGColab: Raw Sequence Processing & Alignment; IGV Germline Variant Visualization
- Homework GGColab
### Lecture 11: Introduction to Low-Pass (Coverage) Whole Genome Sequencing (WGS) for Non-Invasive Prenatal Testing (NIPT) & Pre-implantation Genetic Testing for Aneuploidy (PGT-A) [Duy, Kim] - 25/5/2026, onsite
- PDF
- Lab GGColab: Variant Calling and Filtering
- Homework GGColab
### Lecture 12: Introduction to Targeted Sequencing for Somatic Mutation Detection in Cancer using Tissue & Liquid Biopsy [Hung, Loi] - 01/6/2026, onsite
- PDF
- Lab GGColab: Variant Annotation & Annotation Databases
- Homework GGColab
##
