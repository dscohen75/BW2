# BW2

About this file:  

2126 fetal cardiotocograms (CTGs) were automatically processed and the respective diagnostic features measured.   
The CTGs were also classified by three expert obstetricians and a consensus classification label assigned to each of them.   
Classification was both with respect to a morphologic pattern (A, B, C. …) and to a fetal state (N, S, P).   
Therefore the dataset can be used either for 10-class or 3-class experiments.

Features:  
FileName: of CTG examination  
Date: of the examination  
b: start instant  
e: end instant  
LBE: baseline value (medical expert)  
LB: baseline value (SisPorto)  
AC: accelerations (SisPorto)  
FM: foetal movement (SisPorto)  
UC: uterine contractions (SisPorto)  
ASTV: percentage of time with abnormal short term variability (SisPorto)  
mSTV: mean value of short term variability (SisPorto)  
ALTV: percentage of time with abnormal long term variability (SisPorto)  
mLTV: mean value of long term variability (SisPorto)  
DL: light decelerations  
DS: severe decelerations  
DP: prolonged decelerations  
DR: repetitive decelerations  
Width: histogram width  
Min: low freq. of the histogram  
Max: high freq. of the histogram  
Nmax: number of histogram peaks  
Nzeros: number of histogram zeros  
Mode: histogram mode  
Mean: histogram mean  
Median: histogram median  
Variance: histogram variance  
Tendency: histogram tendency: -1=left assymetric; 0=symmetric; 1=right assymetric  
A: calm sleep  
B: REM sleep  
C: calm vigilance  
D: active vigilance  
SH: shift pattern (A or Susp with shifts)  
AD: accelerative/decelerative pattern (stress situation)  
DE: decelerative pattern (vagal stimulation)  
LD: largely decelerative pattern  
FS: flat-sinusoidal pattern (pathological state)  
SUSP: suspect pattern  
CLASS: Class code (1 to 10) for classes A to SUSP  
NSP:- Normal=1; Suspect=2; Pathologic=3  
