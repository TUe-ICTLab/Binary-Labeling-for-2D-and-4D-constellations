## Binary Labeling for 2D and 4D constellations

### Introduction

The binary labeling of constellations is an important factor to the achievable information rate (AIR) of a constellation. Although normally the mutual information (MI) is used to determine the AIR of a constellation, when the binary labeling is taken into account the GMI is used as described in this publication (https://ieeexplore.ieee.org/document/8240991/similar#similar). 

### Methodology
To calculate both the MI and GMI the Gauss-Hermite approximation is used. The SNR used in the report is defined in the same way as in the same publication as before.  

The algorithm used to determine a good labeling for the constellations is the binary switching algorithm (BSA) as described in this paper (https://ieeexplore.ieee.org/document/64657/authors#authors). The cost function used in the BSA is described in the publication (https://ieeexplore.ieee.org/document/6784555?tp=&amp;arnumber=6784555). 

The target SNR is found by computing the ...

### Notes
- Most of the constellations for which the BSA was executed were taken from Erik Agrell's database https://codes.se/packings/
- Some of the comments in the last column of the tables are taken from Erik Agrell's database https://codes.se/packings/
- The binary labelings reported might not be optimal. If you know of a better labeling (or can find a better labeling), please let us know so we update the table.

### Research Results

The numbers following the constellation have specific meanings in the tables below. For example, in 'QAM2_4',the '2' represents  the dimensionality of the constellation while the '4' refers to  the amount of bits.


Coordinates&Labeling2D https://github.com/TUe-ICTLab/Binary-Labeling-for-2D-and-4D-constellations/blob/main/2D%20Labelings%20Table.md

Coordinates&Labeling4D 
