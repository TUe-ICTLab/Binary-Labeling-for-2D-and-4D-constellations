## Binary Labeling for 2D and 4D constellations

The content below is base on our student's internship report, which was titled 'Binary Labeling for 2D and 4D constellations'.

### Introduction

The binary labeling of constellations is an important factor to the achievable information rate (AIR) of a constellation. Although normally the mutual information (MI) is used to determine the AIR of a constellation, when the binary labeling is taken into account the GMI is used as described in this publication (https://arxiv.org/abs/1709.10393). To calculate both the MI and GMI the Gauss-Hermite approximation is used. The SNR used in the report is defined in the same way as in the same publication as before.  

The algorithm used to determine a good labeling for the constellations is the binary switching algorithm (BSA) as described in this paper (https://ieeexplore.ieee.org/document/64657/authors#authors). The cost function used in the BSA is described in the publication (https://ieeexplore.ieee.org/document/6784555?tp=&amp;arnumber=6784555).  The constellations for which the BSA was executed were all taken from this website (https://codes.se/packings/). 

### Research Results

The numbers following the constellation have specific meanings in the tables below. For example, in 'QAM2_4',the '2' represents  the dimensionality of the constellation while the '4' refers to  the amount of bits.

- Table 1: The SNR(dB) at which these 2D constellations have an NMI (normalized MI) and NGMI (normalized GMI) of 0.8.

  |  Constellation   |    SNR MI    |  SNR GMI   |
  | :--------------: | :----------: | :--------: |
  |   ***4 bits***   |              |            |
  | doublesimplex2_4 |    4.371     |   4.654    |
  |      tri2_4      |    4.980     |   5.791    |
  |      QAM2_4      |  **4.072**   | **4.072**  |
  |   ***8 bits***   |              |            |
  |    square2_8     |    7.746     |   7.992    |
  |       c2_8       |    7.410     |   7.889    |
  |     star2_8      |    7.502     |   8.117    |
  |     hepta2_8     |  **7.215**   |   7.830    |
  |   v29modem2_8    |    7.531     |   8.127    |
  |     modem2_8     |    7.410     |   7.957    |
  |   rectangle2_8   |    8.293     |   8.293    |
  |  doubleQPSK2_8   |    8.098     |   8.107    |
  |      PSK2_8      |    8.098     |   8.107    |
  |      DSQ2_8      |    7.332     | **7.752**  |
  |  ***16 bits***   |              |            |
  |     PSK2_16      |    12.688    |   12.717   |
  |    penta2_16     |  **9.961**   |   10.605   |
  |   multiPSK2_16   |    10.352    |   10.391   |
  |  honeycomb2_16   |    10.521    |   10.590   |
  |     hex2_16      |    10.156    |   10.723   |
  |   v29modem2_16   |    10.039    |   10.493   |
  |   compact2_16    |    10.156    |   10.635   |
  |    cross2_16     |    10.088    |   10.527   |
  |    ennea2_16     |    10.068    |   10.532   |
  |      t2_16       |    10.391    |   10.850   |
  |     tri2_16      |    10.283    |   10.762   |
  |      c2_16       |    10.040    |   10.596   |
  |    dodeca2_16    |    10.195    |   10.371   |
  |     octa2_16     |    10.600    |   11.283   |
  |     QAM2_16      |    10.156    | **10.161** |
  |  ***32 bits***   |              |            |
  |  honeycomb2_32   |    13.039    |   13.410   |
  |    circb2_32     | ***12.658*** |   13.352   |
  |     tri2_32      |    12.839    |   13.562   |
  |    circa2_32     |    12.751    |   13.410   |
  |   multiPSK2_32   |    13.303    |   13.596   |
  |      c2_32       |    12.668    |   14.758   |
  |    cross2_32     |    12.688    | **13.122** |
  |     DSQ2_32      |    12.756    |   13.352   |
  |      tb2_32      |    12.951    |   13.474   |
  |      ta2_32      |    12.688    |   13.420   |
  |  ***64 bits***   |              |            |
  |      c2_64       |    15.244    |   16.318   |
  |    cross2_64     |  **15.225**  |   16.123   |
  |    circb2_64     |    15.332    |   16.704   |
  |    circa2_64     |    15.249    |   16.577   |
  |   circular2_64   |    15.259    |   16.182   |
  |   voronoi2_64    |    15.229    |   16.265   |
  |    modem2_64     |    15.249    |   16.284   |
  |     tri2_64      |    15.361    |   16.396   |
  |  honeycomb2_64   |    15.361    |   16.138   |
  |     QAM2_64      |    15.425    | **15.430** |
  |  ***128 bits***  |              |            |
  | fivecircle2_128  |    17.844    |   19.660   |
  |     tri2_128     |    17.814    |   19.436   |
  |  sixcircle2_128  |    17.810    |   19.777   |
  |      c2_128      |  **17.771**  |   19.450   |
  |    cross2_128    |    17.810    |   19.450   |
  |     DSQ2_128     |    17.902    |   19.782   |
  |      b2_128      |    17.785    | **19.411** |
  |  ***256 bits***  |              |            |
  |      c2_256      |  **20.273**  |   24.365   |
  |     QAM2_256     |    20.469    | **20.488** |
  |  ***512 bits***  |              |            |
  |     DSQ2_512     |    22.917    |   26.657   |
  |    cross2_512    |  **22.800**  | **26.369** |
  | ***1024 bits***  |              |            |
  |    QAM2_1024     |  **25.415**  | **25.488** |

- Table 2: The SNR(dB) at which these 4D constellations have an NMI or NGMI of 0.8

  | Constellation  |  SNR MI   |  SNR GMI   |
  | :------------: | :-------: | :--------: |
  |  ***4 bits***  |           |            |
  |    ortho4_4    |   1.707   |   2.225    |
  |     PPM4_4     |   1.707   |   2.225    |
  | tetrahedron4_4 | **0.469** | **0.977**  |
  |  ***8 bits***  |           |            |
  |      l4_8      | **2.098** | **2.752**  |
  |   voronoi4_8   |   3.166   |   3.166    |
  |   parity4_8    |   2.107   |   2.762    |
  |   biortho4_8   |   2.107   |   2.757    |
  |      c4_8      |   2.107   | **2.752**  |
  | ***16 bits***  |           |            |
  |    cube4_16    |   4.068   | **4.068**  |
  |     l4_16      |   4.127   |   4.933    |
  |     c4_16      | **3.893** |   4.693    |
  | SO-PM-QPSK4_16 |   4.278   |   4.688    |
  |  dicyclic4_16  |   4.541   |   4.751    |
  |    QAM4_16     |   4.072   |   4.072    |
  | ***32 bits***  |           |            |
  |  voronoi4_32   |   5.824   | **6.278**  |
  |     b4_32      |   5.619   |   6.420    |
  |     l4_32      |   5.541   |   6.400    |
  |     c4_32      | **5.502** |   6.430    |
  |   SP-QAM4_32   |   5.717   |   6.425    |
  | ***64 bits***  |           |            |
  |     l4_64      |   7.063   |   8.260    |
  |     w4_64      | **7.010** |   8.211    |
  |     b4_64      |   7.176   | **8.177**  |
  | ***128 bits*** |           |            |
  |     l4_128     | **8.430** |   9.924    |
  |  SP-QAM4_128   |   8.585   | **9.399**  |
  | ***256 bits*** |           |            |
  |  voronoi4_256  |   9.790   |   11.685   |
  |     w4_256     | **9.778** |   11.614   |
  |     a4_256     |   9.780   |   11.682   |
  |    ab4_256     |   9.780   |   11.709   |
  |    QAM4_256    |  10.156   | **10.161** |

>    In table 2, No constellation with a size larger than 256 was optimized, as this would be too time consuming.