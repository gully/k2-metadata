
Ecliptic Plane Input Catalog
(49,984,908 sources as of July 12, 2016)
(50,192,072 sources as of September 29, 2016)
(50,194,708 sources as of March 31, 2017)
(50,545,738 sources as of July 6, 2017)

Since April, 2017 the downloadable version of the 
EPIC table is stored as five pipe-delimited (i.e., "|")
gzipped ASCII files. The files are divided by ID as shown 
below. Each is about 1/2 GB.

    ID Range            # of entries   File Name
201000001 to 211161829   10074319   epic_1_06jun17.txt.gz
211161830 to 221323658   10161829   epic_2_06jun17.txt.gz
221323659 to 231485487    9985933   epic_3_06jun17.txt.gz
231485488 to 241647316   10161829   epic_4_06jun17.txt.gz
241647317 to 251809144   10161828   epic_5_06jun17.txt.gz

See the EPIC documentation (https://archive.stsci.edu/k2/epic.pdf) for more details.


Columns definitions:

---------------------------------------------------------------------------------
### Identifiers & Flags
#1  ID          I10           ... K2 Input Catalog Identifier
#2  HIP         I8            ... Hipparcos Identifier
#3  TYC         A15           ... Tycho2 Identifier
#4  UCAC        A15           ... UCAC4 Identifier
#5  2MASS       A20           ... 2MASS Identifier
#6  SDSS        A20           ... SDSS DR9 Identifier
#7  Objtype     A10           ... Object Type [STAR,EXTENDED]
#8  Kepflag     A5            ... Kepler Magnitude Flag [gri,BV,JHK,J]
#9  StpropFlag  A5            ... Stellar Properties Flag [not used]
---------------------------------------------------------------------------------
### Observables
#10 RA          D10.6         ... Right Ascension JD2000 (Deg)
#11 DEC         D10.6         ... Declination JD2000 (Deg)
#12 pmRA        D10.3         ... Proper motion in RA (mas/yr)
#13 e_pmRA      D10.3         ... Uncertainty in Proper motion in RA (mas/yr)
#14 pmDEC       D10.3         ... Proper motion in DEC (mas/yr)
#15 e_pmDEC     D10.3         ... Uncertainty in Proper motion in DEC (mas/yr)
#16 plx         D10.3         ... Hipparcos parallax (mas)
#17 e_plx       D10.3         ... Uncertainty in parallax (mas)
#18 Bmag        D6.3          ... Johnson B Magnitude (mag)
#19 e_Bmag      D6.3          ... Uncertainty in Johnson B Magnitude (mag)
#20 Vmag        D6.3          ... Johnson V Magnitude (mag)
#21 e_Vmag      D6.3          ... Uncertainty in Johnson V Magnitude (mag)
#22 umag        D6.3          ... Sloan u Magnitude (mag)
#23 e_umag      D6.3          ... Uncertainty in Sloan u Magnitude (mag)
#24 gmag        D6.3          ... Sloan g Magnitude (mag)
#25 e_gmag      D6.3          ... Uncertainty in Sloan g Magnitude (mag)
#26 rmag        D6.3          ... Sloan r Magnitude (mag)
#27 e_rmag      D6.3          ... Uncertainty in Sloan r Magnitude (mag)
#28 imag        D6.3          ... Sloan i Magnitude (mag)
#29 e_imag      D6.3          ... Uncertainty in Sloan i Magnitude (mag)
#30 zmag        D6.3          ... Sloan z Magnitude (mag)
#31 e_zmag      D6.3          ... Uncertainty in Sloan z Magnitude (mag)
#32 Jmag        D6.3          ... 2MASS J Magnitude (mag)
#33 e_Jmag      D6.3          ... Uncertainty in 2MASS J Magnitude (mag)
#34 Hmag        D6.3          ... 2MASS H Magnitude (mag)
#35 e_Hmag      D6.3          ... Uncertainty in 2MASS H Magnitude (mag)
#36 Kmag        D6.3          ... 2MASS K Magnitude (mag)
#37 e_Kmag      D6.3          ... Uncertainty in 2MASS K Magnitude (mag)
#38 W1mag       D6.3          ... WISE W1 Magnitude (mag)
#39 e_W1mag     D6.3          ... Uncertainty in WISE W1 Magnitude (mag)
#40 W2mag       D6.3          ... WISE W2 Magnitude (mag)
#41 e_W2mag     D6.3          ... Uncertainty in WISE W2 Magnitude (mag)
#42 W3mag       D6.3          ... WISE W3 Magnitude (mag)
#43 e_W3mag     D6.3          ... Uncertainty in WISE W3 Magnitude (mag)
#44 W4mag       D6.3          ... WISE W4 Magnitude (mag)
#45 e_W4mag     D6.3          ... Uncertainty in WISE W4 Magnitude (mag)
---------------------------------------------------------------------------------
### Derived Properties
#46 Kp          D6.3          ... Kepler Magnitude (mag)
#47 Teff        D6.0          ... Effective Temperature (K)
#48 e_Teff      D6.0          ... Uncertainty in Effective Temperature (K)
#49 logg        D6.3          ... log Surface Gravity (cgs)
#50 e_logg      D6.3          ... Uncertainty in log Surface Gravity (cgs)
#51 [Fe/H]      D6.3          ... Metallicity (dex)
#52 e_[Fe/H]    D6.3          ... Uncertainty in Metallicity (dex)
#53 Rad         D8.3          ... Stellar Radius (solar units)
#54 e_Rad       D8.3          ... Uncertainty in Stellar Radius (solar units)
#55 Mass        D8.3          ... Stellar Mass (solar units)
#56 e_Mass      D8.3          ... Uncertainty in Stellar Mass (solar units)
#57 rho         E10.3         ... Stellar Density (solar units)
#58 e_rho       E10.3         ... Uncertainty in Stellar Density (solar units)
#59 Lum         E10.3         ... Stellar Luminosity (solar units)
#60 e_Lum       E10.3         ... Uncertainty in Stellar Luminosity (solar units)
#61 d           D8.1          ... Distance (pc)
#62 e_d         D8.1          ... Uncertainty in Distance (solar units)
#63 E(B-V)      D6.3          ... Extinction (mag)
---------------------------------------------------------------------------------
### Additional Information
#64 NOMAD       A20           ... NOMAD1 Identifier [for sources with supplemented NOMAD1 proper motions]
#65 Mflg        A20           ... 2MASS Flags [Qflg-Rflg-Bflg-Cflg-Xflg-Aflg]
#66 prox        D6.3          ... 2MASS nearest neighbor distance (arcsec)
#67 k2_avail_flag             ... 1=target was observed, 0=target not observedAre you sure it
