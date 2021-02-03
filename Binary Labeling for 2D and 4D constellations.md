## Binary Labeling for 2D and 4D constellations

The content below is base on our student's internship report, which was titled 'Binary Labeling for 2D and 4D constellations'.

### Introduction

The binary labeling of constellations is an important factor to the achievable information rate (AIR) of a constellation. Although normally the mutual information (MI) is used to determine the AIR of a constellation, when the binary labeling is taken into account the GMI is used as described in this publication (https://arxiv.org/abs/1709.10393). To calculate both the MI and GMI the Gauss-Hermite approximation is used. The SNR used in the report is defined in the same way as in the same publication as before.  

The algorithm used to determine a good labeling for the constellations is the binary switching algorithm (BSA) as described in this paper (https://ieeexplore.ieee.org/document/64657/authors#authors). The cost function used in the BSA is described in the publication (https://ieeexplore.ieee.org/document/6784555?tp=&amp;arnumber=6784555).  The constellations for which the BSA was executed were all taken from this website (https://codes.se/packings/). 

### Research Results

The numbers following the constellation have specific meanings in the tables below. For example, in 'QAM2_4',the '2' represents  the dimensionality of the constellation while the '4' refers to  the amount of bits.

- Table 1: The SNR(dB) at which these 2D constellations have an NMI (normalized MI) and NGMI (normalized GMI) of 0.8.

  |      Constellation      |    SNR MI    |  SNR GMI   |                    Reference For Labeling                    |
  | :---------------------: | :----------: | :--------: | :----------------------------------------------------------: |
  | ***2 bits/2D-symbol***  |              |            |                                                              |
  |    doublesimplex2_4     |    4.371     |   4.654    | [doublesimplex2_4](https://github.com/Yeming-Ni/labeling2D/blob/main/doublesimplex2_4.txt.mat) |
  |         tri2_4          |    4.980     |   5.791    | [tri2_4](https://github.com/Yeming-Ni/labeling2D/blob/main/tri2_4.txt.mat) |
  |         QAM2_4          |  **4.072**   | **4.072**  |                        Gray labeling                         |
  | ***3 bits/2D-symbol***  |              |            |                                                              |
  |        square2_8        |    7.746     |   7.992    | [square2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/square2_8.txt.mat) |
  |          c2_8           |    7.410     |   7.889    | [c2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_8.txt.mat) |
  |         star2_8         |    7.502     |   8.117    | [star2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/star2_8.txt.mat) |
  |        hepta2_8         |  **7.215**   |   7.830    | [hepta2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/hepta2_8.txt.mat) |
  |       v29modem2_8       |    7.531     |   8.127    | [v29modem2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/v29modem2_8.txt.mat) |
  |        modem2_8         |    7.410     |   7.957    | [modem2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/modem2_8.txt.mat) |
  |      rectangle2_8       |    8.293     |   8.293    | [rectangle2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/rectangle2_8.txt.mat) |
  |      doubleQPSK2_8      |    8.098     |   8.107    | [doubleQPSK2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/doubleQPSK2_8.txt.mat) |
  |         PSK2_8          |    8.098     |   8.107    | [PSK2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/PSK2_8.txt.mat) |
  |         DSQ2_8          |    7.332     | **7.752**  | [DSQ2_8](https://github.com/Yeming-Ni/labeling2D/blob/main/DSQ2_8.txt.mat) |
  | ***4 bits/2D-symbol***  |              |            |                                                              |
  |         PSK2_16         |    12.688    |   12.717   | [PSK2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/PSK2_16.txt.mat) |
  |        penta2_16        |  **9.961**   |   10.605   | [penta2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/penta2_16.txt.mat) |
  |      multiPSK2_16       |    10.352    |   10.391   | [multiPSK2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/multiPSK2_16.txt.mat) |
  |      honeycomb2_16      |    10.521    |   10.590   | [honeycomb2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/honeycomb2_16.txt.mat) |
  |         hex2_16         |    10.156    |   10.723   | [hex2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/hex2_16.txt.mat) |
  |      v29modem2_16       |    10.039    |   10.493   | [v29modem2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/v29modem2_16.txt.mat) |
  |       compact2_16       |    10.156    |   10.635   | [compact2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/compact2_16.txt.mat) |
  |        cross2_16        |    10.088    |   10.527   | [cross2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/cross2_16.txt.mat) |
  |        ennea2_16        |    10.068    |   10.532   | [ennea2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/ennea2_16.txt.mat) |
  |          t2_16          |    10.391    |   10.850   | [t2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/t2_16.txt.mat) |
  |         tri2_16         |    10.283    |   10.762   | [tri2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/tri2_16.txt.mat) |
  |          c2_16          |    10.040    |   10.596   | [c2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_16.txt.mat) |
  |       dodeca2_16        |    10.195    |   10.371   | [dodeca2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/dodeca2_16.txt.mat) |
  |        octa2_16         |    10.600    |   11.283   | [octa2_16](https://github.com/Yeming-Ni/labeling2D/blob/main/octa2_16.txt.mat) |
  |         QAM2_16         |    10.156    | **10.161** |                        Gray labeling                         |
  | ***5 bits/2D-symbol***  |              |            |                                                              |
  |      honeycomb2_32      |    13.039    |   13.410   | [honeycomb2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/honeycomb2_32.txt.mat) |
  |        circb2_32        | ***12.658*** |   13.352   | [circb2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/circb2_32.txt.mat) |
  |         tri2_32         |    12.839    |   13.562   | [tri2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/tri2_32.txt.mat) |
  |        circa2_32        |    12.751    |   13.410   | [circa2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/circa2_32.txt.mat) |
  |      multiPSK2_32       |    13.303    |   13.596   | [multiPSK2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/multiPSK2_32.txt.mat) |
  |          c2_32          |    12.668    |   14.758   | [c2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_32.txt.mat) |
  |        cross2_32        |    12.688    | **13.122** | [cross2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/cross2_32.txt.mat) |
  |         DSQ2_32         |    12.756    |   13.352   | [DSQ2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/DSQ2_32.txt.mat) |
  |         tb2_32          |    12.951    |   13.474   | [tb2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/tb2_32.txt.mat) |
  |         ta2_32          |    12.688    |   13.420   | [ta2_32](https://github.com/Yeming-Ni/labeling2D/blob/main/ta2_32.txt.mat) |
  | ***6 bits/2D-symbol***  |              |            |                                                              |
  |          c2_64          |    15.244    |   16.318   | [c2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_64.txt.mat) |
  |        cross2_64        |  **15.225**  |   16.123   | [cross2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/cross2_64.txt.mat) |
  |        circb2_64        |    15.332    |   16.704   | [circb2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/circb2_64.txt.mat) |
  |        circa2_64        |    15.249    |   16.577   | [circa2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/circa2_64.txt.mat) |
  |      circular2_64       |    15.259    |   16.182   | [circular2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/circular2_64.txt.mat) |
  |       voronoi2_64       |    15.229    |   16.265   | [voronoi2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/voronoi2_64.txt.mat) |
  |        modem2_64        |    15.249    |   16.284   | [modem2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/modem2_64.txt.mat) |
  |         tri2_64         |    15.361    |   16.396   | [tri2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/tri2_64.txt.mat) |
  |      honeycomb2_64      |    15.361    |   16.138   | [honeycomb2_64](https://github.com/Yeming-Ni/labeling2D/blob/main/honeycomb2_64.txt.mat) |
  |         QAM2_64         |    15.425    | **15.430** |                        Gray labeling                         |
  | ***7 bits/2D-symbol***  |              |            |                                                              |
  |     fivecircle2_128     |    17.844    |   19.660   | [fivecircle2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/fivecircle2_128.txt.mat) |
  |        tri2_128         |    17.814    |   19.436   | [tri2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/tri2_128.txt.mat) |
  |     sixcircle2_128      |    17.810    |   19.777   | [sixcircle2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/sixcircle2_128.txt.mat) |
  |         c2_128          |  **17.771**  |   19.450   | [c2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_128.txt.mat) |
  |       cross2_128        |    17.810    |   19.450   | [cross2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/cross2_128.txt.mat) |
  |        DSQ2_128         |    17.902    |   19.782   | [DSQ2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/DSQ2_128.txt.mat) |
  |         b2_128          |    17.785    | **19.411** | [b2_128](https://github.com/Yeming-Ni/labeling2D/blob/main/b2_128.txt.mat) |
  | ***8 bits/2D-symbol***  |              |            |                                                              |
  |         c2_256          |  **20.273**  |   24.365   | [c2_256](https://github.com/Yeming-Ni/labeling2D/blob/main/c2_256.txt.mat) |
  |        QAM2_256         |    20.469    | **20.488** |                        Gray labeling                         |
  | ***9 bits/2D-symbol***  |              |            |                                                              |
  |        DSQ2_512         |    22.917    |   26.657   | [DSQ2_512](https://github.com/Yeming-Ni/labeling2D/blob/main/DSQ2_512.txt.mat) |
  |       cross2_512        |  **22.800**  | **26.369** | [cross2_512](https://github.com/Yeming-Ni/labeling2D/blob/main/cross2_512.txt.mat) |
  | ***10 bits/2D-symbol*** |              |            |                                                              |
  |        QAM2_1024        |  **25.415**  | **25.488** |                        Gray labeling                         |

- Table 2: The SNR(dB) at which these 4D constellations have an NMI or NGMI of 0.8

  |     Constellation      |  SNR MI   |  SNR GMI   |                    Reference For Labeling                    |
  | :--------------------: | :-------: | :--------: | :----------------------------------------------------------: |
  | ***2 bit/4D-symbol***  |           |            |                                                              |
  |        ortho4_4        |   1.707   |   2.225    | [ortho4_4](https://github.com/Yeming-Ni/labeling4D/blob/main/ortho4_4.txt.mat) |
  |         PPM4_4         |   1.707   |   2.225    | [PPM4_4](https://github.com/Yeming-Ni/labeling4D/blob/main/PPM4_4.txt.mat) |
  |     tetrahedron4_4     | **0.469** | **0.977**  | [tetrahedron4_4](https://github.com/Yeming-Ni/labeling4D/blob/main/tetrahedron4_4.txt.mat) |
  | ***3 bits/4D-symbol*** |           |            |                                                              |
  |          l4_8          | **2.098** | **2.752**  | [l4_8](https://github.com/Yeming-Ni/labeling4D/blob/main/l4_8.txt.mat) |
  |       voronoi4_8       |   3.166   |   3.166    | [voronoi4_8](https://github.com/Yeming-Ni/labeling4D/blob/main/voronoi4_8.txt.mat) |
  |       parity4_8        |   2.107   |   2.762    | [parity4_8](https://github.com/Yeming-Ni/labeling4D/blob/main/parity4_8.txt.mat) |
  |       biortho4_8       |   2.107   |   2.757    | [biortho4_8](https://github.com/Yeming-Ni/labeling4D/blob/main/biortho4_8.txt.mat) |
  |          c4_8          |   2.107   | **2.752**  | [c4_8](https://github.com/Yeming-Ni/labeling4D/blob/main/c4_8.txt.mat) |
  | ***4 bits/4D-symbol*** |           |            |                                                              |
  |        cube4_16        |   4.068   | **4.068**  | [cube4_16](https://github.com/Yeming-Ni/labeling4D/blob/main/cube4_16.txt.mat) |
  |         l4_16          |   4.127   |   4.933    | [l4_16](https://github.com/Yeming-Ni/labeling4D/blob/main/l4_16.txt.mat) |
  |         c4_16          | **3.893** |   4.693    | [c4_16](https://github.com/Yeming-Ni/labeling4D/blob/main/c4_16.txt.mat) |
  |     SO-PM-QPSK4_16     |   4.278   |   4.688    | [SO-PM-QPSK4_16](https://github.com/Yeming-Ni/labeling4D/blob/main/SO-PM-QPSK4_16.txt.mat) |
  |      dicyclic4_16      |   4.541   |   4.751    | [dicyclic4_16](https://github.com/Yeming-Ni/labeling4D/blob/main/dicyclic4_16.txt.mat) |
  |        QAM4_16         |   4.072   |   4.072    |                        Gray labeling                         |
  | ***5 bits/4D-symbol*** |           |            |                                                              |
  |      voronoi4_32       |   5.824   | **6.278**  | [voronoi4_32](https://github.com/Yeming-Ni/labeling4D/blob/main/voronoi4_32.txt.mat) |
  |         b4_32          |   5.619   |   6.420    | [b4_32](https://github.com/Yeming-Ni/labeling4D/blob/main/b4_32.txt.mat) |
  |         l4_32          |   5.541   |   6.400    | [l4_32](https://github.com/Yeming-Ni/labeling4D/blob/main/l4_32.txt.mat) |
  |         c4_32          | **5.502** |   6.430    | [c4_32](https://github.com/Yeming-Ni/labeling4D/blob/main/c4_32.txt.mat) |
  |       SP-QAM4_32       |   5.717   |   6.425    |                                                              |
  | ***6 bits/4D-symbol*** |           |            |                                                              |
  |         l4_64          |   7.063   |   8.260    | [l4_64](https://github.com/Yeming-Ni/labeling4D/blob/main/l4_64.txt.mat) |
  |         w4_64          | **7.010** |   8.211    | [w4_64](https://github.com/Yeming-Ni/labeling4D/blob/main/w4_64.txt.mat) |
  |         b4_64          |   7.176   |   8.177    | [b4_64](https://github.com/Yeming-Ni/labeling4D/blob/main/b4_64.txt.mat) |
  |        6b2A8PSK        |   7.337   |   7.887    | [6b2A8PSK](https://github.com/Yeming-Ni/labeling4D/blob/main/X_4D_2A_8PSK_6b.mat) |
  |        4D-64PRS        |   7.268   | **7.435**  | [4D-64PRS](https://github.com/Yeming-Ni/labeling4D/blob/main/X_4D_64_optimized_for_8dB.mat) |
  | ***7 bits/4D-symbol*** |           |            |                                                              |
  |         l4_128         | **8.430** |   9.924    | [l4_128](https://github.com/Yeming-Ni/labeling4D/blob/main/l4_128.txt.mat) |
  |      SP-QAM4_128       |   8.585   |   9.399    |                                                              |
  |        7b2A8PSK        |   9.169   |   9.224    | [7b2A8PSK](https://github.com/Yeming-Ni/labeling4D/blob/main/X_4D_2A_8PSK_7b.mat) |
  |        4D-OS128        |   8.641   | **8.829**  | [4D-OS128](https://github.com/Yeming-Ni/labeling4D/blob/main/X_4D_OS128.mat) |
  | ***8 bits/4D-symbol*** |           |            |                                                              |
  |      voronoi4_256      |   9.790   |   11.685   | [voronoi4_256](https://github.com/Yeming-Ni/labeling4D/blob/main/voronoi4_256.txt.mat) |
  |         w4_256         | **9.778** |   11.614   | [w4_256](https://github.com/Yeming-Ni/labeling4D/blob/main/w4_256.txt.mat) |
  |         a4_256         |   9.780   |   11.682   | [a4_256](https://github.com/Yeming-Ni/labeling4D/blob/main/a4_256.txt.mat) |
  |        ab4_256         |   9.780   |   11.709   | [ab4_256](https://github.com/Yeming-Ni/labeling4D/blob/main/ab4_256.txt.mat) |
  |        QAM4_256        |  10.156   | **10.161** |                        Gray labeling                         |

>    In table 2, no constellation with a size larger than 256 was optimized, as this would be too time consuming.