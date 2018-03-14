#Transcriptomal changes in Mesenchymal stem cells exposed to spina cord environment

**Hypothesis:** *The transcriptome of bone marrow derived mesenchymal stem cells (MSCs) transplanted into a spinal cord injury environment is altered as compared to MSCs transplanted into uninjured spinal cord.*  

**Experimental setup & sequencing:** mCherry+MSCs were transplanted into injured (75 kdyn contusion injury, 24h post SCI) or uninjured spinal cord using a glas capillary pipette. C57BL/6J female mice were utilized. At 7 days post transplantation the mCherry+MSCs were FACSed. Injured and uninjured (when applicable) were used for setting positive mCherry gate. Total RNA, digested of DNase, was isolated and sequenced (125 cycles paired-end) in two lane using the HiSeq2500 system and v4 sequencing chemistry (Illumina Inc.) performed by the SNP&SEQ Technology Platform (Stockholm, Sweden).  

**Data analysis:** A read count matrix was obtained from the sequencing core facility. Data was analyed using the edgeR and limma packages (both available through bioconductor.org) using R version 3.4.1. Two additional key packages used were ggplot2 and data.table.  



