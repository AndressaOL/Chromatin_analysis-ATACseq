# ${{\color{Orange}\Huge{\textsf{Chromatin data analysis (ATAC-seq)}}}}\$ :panda_face:  <br />

Repertoire of Pipelines and Jobs to perform Chromatin Data Analysis (ATAC-Seq)  <br />

## Contents:
:o:  FRiP Score   <br />
:link: https://github.com/AndressaOL/Chromatin_analysis-ATACseq/blob/main/FRiP_Score.sh
**Fraction of reads in peaks (FRiP):** FRiP Score essential to evaluate the Peaks Quality. *more details:* https://yiweiniu.github.io/blog/2019/03/Calculate-FRiP-score/ <br />
- Request data: *.bam files & *Peaks files (Narrow or broad)
- To calculate the FRiPs run the script 
```
bash FRiP_Score.sh  ${bam file}  ${broadPeak or NarrowPeak}
``` 
*using MACS2 ouptuts

