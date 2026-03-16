# Wang2
Supporting information and code for paper TCR activation repositions Nck and Lck binding sites in CD3 cytoplasmic tails further from the membrane by Liangyu Wang, Diana Gil, and John F. Cannon

Build Files and scripts to build models  
makeTorsions.cpp: Write tleap impose statements based on HGBLE string. 
makeHGBLE.cpp : Output random HGBLE string based on sequence and frequency table. 
HGBLEfreq2: Secondary structure frequencies for IDR's. 

Run Job scripts to run MD of models  
tcr33minR.sh: Minimization of tcr33b,c,s and tcr35s on Rockfish. 
