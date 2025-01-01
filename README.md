# FMC_pinout
 This repo has all the FMC connector pinouts


# FMC LPC
|Column\row|C  |D              |G          |H          |
|- |-          |-              |-          |-          |
|1 |GND        |PG_C2M         |GND        |VREF_A_M2C |
|2 |DP0_C2M_P  |GND            |CLK1_M2C_P |PRSNT_M2C_L|
|3 |DP0_C2M_N  |GND            |CLK1_M2C_N |GND        |
|4 |GND        |GBTCLK0_M2C_P  |GND        |CLK0_M2C_P |
|5 |GND        |GBTCLK0_M2C_N  |GND        |CLK0_M2C_N |
|6 |DP0_M2C_P  |GND            |LA00_P_CC  |GND        |
|7 |DP0_M2C_N  |GND            |LA00_N_CC  |LA02_P     |
|8 |GND        |LA01_P_CC      |GND        |LA02_N     |
|9 |GND        |LA01_N_CC      |LA03_P     |GND        |
|10|LA06_P     |GND            |LA03_N     |LA04_P     |
|11|LA06_N     |LA05_P         |GND        |LA04_N     |
|12|GND        |LA05_N         |LA08_P     |GND        |
|13|GND        |GND            |LA08_N     |LA07_P     |
|14|LA10_P     |LA09_P         |GND        |LA07_N     |
|15|LA10_N     |LA09_N         |LA12_P     |GND        |
|16|GND        |GND            |LA12_N     |LA11_P     |
|17|GND        |LA13_P         |GND        |LA11_N     |
|18|LA14_P     |LA13_N         |LA16_P     |GND        |
|19|LA14_N     |GND            |LA16_N     |LA15_P     |
|20|GND        |LA17_P_CC      |GND        |LA15_N     |
|21|GND        |LA17_N_CC      |LA20_P     |GND        |
|22|LA18_P_CC  |GND            |LA20_N     |LA19_P     |
|23|LA18_N_CC  |LA23_P         |GND        |LA19_N     |
|24|GND        |LA23_N         |LA22_P     |GND        |
|25|GND        |GND            |LA22_N     |LA21_P     |
|26|LA27_P     |LA26_P         |GND        |LA21_N     |
|27|LA27_N     |LA26_N         |LA25_P     |GND        |
|28|GND        |GND            |LA25_N     |LA24_P     |
|29|GND        |TCK            |GND        |LA24_N     |
|30|SCL        |TDI            |LA29_P     |GND        |
|31|SDA        |TDO            |LA29_N     |LA28_P     |
|32|GND        |3P3VAUX        |GND        |LA28_N     |
|33|GND        |TMS            |LA31_P     |GND        |
|34|GA0        |TRST_L         |LA31_N     |LA30_P     |
|35|12P0V      |GA1            |GND        |LA30_N     |
|36|GND        |3P3V           |LA33_P     |GND        |
|37|12P0V      |GND            |LA33_N     |LA32_P     |
|38|GND        |3P3V           |GND        |LA32_N     |
|39|3P3V       |GND            |VADJ       |GND        |
|40|GND        |3P3V           |GND        |VADJ       |


# FMC HPC
|Column\row|A   |B              |C          |D              |E          |F          |G          |H          |J              |K              |
|- |-           |-              |-          |-              |-          |-          |-          |-          |-              |-              |
|1 |GND         |CLK_DIR        |GND        |PG_C2M         |GND        |PG_M2C     |GND        |VREF_A_M2C |GND            |VREF_B_M2C     |
|2 |DP1_M2C_P   |GND            |DP0_C2M_P  |GND            |HA01_P_CC  |GND        |CLK1_M2C_P |PRSNT_M2C_L|CLK3_BIDIR_P   |GND            |
|3 |DP1_M2C_N   |GND            |DP0_C2M_N  |GND            |HA01_N_CC  |GND        |CLK1_M2C_N |GND        |CLK3_BIDIR_N   |GND            |
|4 |GND         |DP9_M2C_P      |GND        |GBTCLK0_M2C_P  |GND        |HA00_P_CC  |GND        |CLK0_M2C_P |GND            |CLK2_BIDIR_P   |
|5 |GND         |DP9_M2C_N      |GND        |GBTCLK0_M2C_N  |GND        |HA00_N_CC  |GND        |CLK0_M2C_N |GND            |CLK2_BIDIR_N   |
|6 |DP2_M2C_P   |GND            |DP0_M2C_P  |GND            |HA05_P     |GND        |LA00_P_CC  |GND        |HA03_P         |GND            |
|7 |DP2_M2C_N   |GND            |DP0_M2C_N  |GND            |HA05_N     |HA04_P     |LA00_N_CC  |LA02_P     |HA03_N         |HA02_P         |
|8 |GND         |DP8_M2C_P      |GND        |LA01_P_CC      |GND        |HA04_N     |GND        |LA02_N     |GND            |HA02_N         |
|9 |GND         |DP8_M2C_N      |GND        |LA01_N_CC      |HA09_P     |GND        |LA03_P     |GND        |HA07_P         |GND            |
|10|DP3_M2C_P   |GND            |LA06_P     |GND            |HA09_N     |HA08_P     |LA03_N     |LA04_P     |HA07_N         |HA06_P         |
|11|DP3_M2C_N   |GND            |LA06_N     |LA05_P         |GND        |HA08_N     |GND        |LA04_N     |GND            |HA06_N         |
|12|GND         |DP7_M2C_P      |GND        |LA05_N         |HA13_P     |GND        |LA08_P     |GND        |HA11_P         |GND            |
|13|GND         |DP7_M2C_N      |GND        |GND            |HA13_N     |HA12_P     |LA08_N     |LA07_P     |HA11_N         |HA10_P         |
|14|DP4_M2C_P   |GND            |LA10_P     |LA09_P         |GND        |HA12_N     |GND        |LA07_N     |GND            |HA10_N         |
|15|DP4_M2C_N   |GND            |LA10_N     |LA09_N         |HA16_P     |GND        |LA12_P     |GND        |HA14_P         |GND            |
|16|GND         |DP6_M2C_P      |GND        |GND            |HA16_N     |HA15_P     |LA12_N     |LA11_P     |HA14_N         |HA17_P_CC      |
|17|GND         |DP6_M2C_N      |GND        |LA13_P         |GND        |HA15_N     |GND        |LA11_N     |GND            |HA17_N_CC      |
|18|DP5_M2C_P   |GND            |LA14_P     |LA13_N         |HA20_P     |GND        |LA16_P     |GND        |HA18_P         |GND            |
|19|DP5_M2C_N   |GND            |LA14_N     |GND            |HA20_N     |HA19_P     |LA16_N     |LA15_P     |HA18_N         |HA21_P         |
|20|GND         |GBTCLK1_M2C_P  |GND        |LA17_P_CC      |GND        |HA19_N     |GND        |LA15_N     |GND            |HA21_N         |
|21|GND         |GBTCLK1_M2C_N  |GND        |LA17_N_CC      |HB03_P     |GND        |LA20_P     |GND        |HA22_P         |GND            |
|22|DP1_C2M_P   |GND            |LA18_P_CC  |GND            |HB03_N     |HB02_P     |LA20_N     |LA19_P     |HA22_N         |HA23_P         |
|23|DP1_C2M_N   |GND            |LA18_N_CC  |LA23_P         |GND        |HB02_N     |GND        |LA19_N     |GND            |HA23_N         |
|24|GND         |DP9_C2M_P      |GND        |LA23_N         |HB05_P     |GND        |LA22_P     |GND        |HB01_P         |GND            |
|25|GND         |DP9_C2M_N      |GND        |GND            |HB05_N     |HB04_P     |LA22_N     |LA21_P     |HB01_N         |HB00_P_CC      |
|26|DP2_C2M_P   |GND            |LA27_P     |LA26_P         |GND        |HB04_N     |GND        |LA21_N     |GND            |HB00_N_CC      |
|27|DP2_C2M_N   |GND            |LA27_N     |LA26_N         |HB09_P     |GND        |LA25_P     |GND        |HB07_P         |GND            |
|28|GND         |DP8_C2M_P      |GND        |GND            |HB09_N     |HB08_P     |LA25_N     |LA24_P     |HB07_N         |HB06_P_CC      |
|29|GND         |DP8_C2M_N      |GND        |TCK            |GND        |HB08_N     |GND        |LA24_N     |GND            |HB06_N_CC      |
|30|DP3_C2M_P   |GND            |SCL        |TDI            |HB13_P     |GND        |LA29_P     |GND        |HB11_P         |GND            |
|31|DP3_C2M_N   |GND            |SDA        |TDO            |HB13_N     |HB12_P     |LA29_N     |LA28_P     |HB11_N         |HB10_P         |
|32|GND         |DP7_C2M_P      |GND        |3P3VAUX        |GND        |HB12_N     |GND        |LA28_N     |GND            |HB10_N         |
|33|GND         |DP7_C2M_N      |GND        |TMS            |HB19_P     |GND        |LA31_P     |GND        |HB15_P         |GND            |
|34|DP4_C2M_P   |GND            |GA0        |TRST_L         |HB19_N     |HB16_P     |LA31_N     |LA30_P     |HB15_N         |HB14_P         |
|35|DP4_C2M_N   |GND            |12P0V      |GA1            |GND        |HB16_N     |GND        |LA30_N     |GND            |HB14_N         |
|36|GND         |DP6_C2M_P      |GND        |3P3V           |HB21_P     |GND        |LA33_P     |GND        |HB18_P         |GND            |
|37|GND         |DP6_C2M_N      |12P0V      |GND            |HB21_N     |HB20_P     |LA33_N     |LA32_P     |HB18_N         |HB17_P_CC      |
|38|DP5_C2M_P   |GND            |GND        |3P3V           |GND        |HB20_N     |GND        |LA32_N     |GND            |HB17_N_CC      |
|39|DP5_C2M_N   |GND            |3P3V       |GND            |VADJ       |GND        |VADJ       |GND        |VIO_B_M2C      |GND            |
|40|GND         |RES0           |GND        |3P3V           |GND        |VADJ       |GND        |VADJ       |GND            |VIO_B_M2C      |


# FMC+ (HPSC)
|Column\row|A   |B              |C          |D              |E          |F          |G          |H          |J              |K              |L              |M          |Y          |Z                  |
|- |-           |-              |-          |-              |-          |-          |-          |-          |-              |-              |-              |-          |-          |-                  |
|1 |GND         |CLK_DIR        |GND        |PG_C2M         |GND        |PG_M2C     |GND        |VREF_A_M2C |GND            |VREF_B_M2C     |RES1           |GND        |GND        |HSPC_PRSNT_M2C_L   |
|2 |DP1_M2C_P   |GND            |DP0_C2M_P  |GND            |HA01_P_CC  |GND        |CLK1_M2C_P |PRSNT_M2C_L|CLK3_BIDIR_P   |GND            |GND            |DP23_M2C_P |DP23_C2M_P |GND                |
|3 |DP1_M2C_N   |GND            |DP0_C2M_N  |GND            |HA01_N_CC  |GND        |CLK1_M2C_N |GND        |CLK3_BIDIR_N   |GND            |GND            |DP23_M2C_N |DP23_C2M_N |GND                |
|4 |GND         |DP9_M2C_P      |GND        |GBTCLK0_M2C_P  |GND        |HA00_P_CC  |GND        |CLK0_M2C_P |GND            |CLK2_BIDIR_P   |GBTCLK4_M2C_P  |GND        |GND        |DP22_C2M_P         |
|5 |GND         |DP9_M2C_N      |GND        |GBTCLK0_M2C_N  |GND        |HA00_N_CC  |GND        |CLK0_M2C_N |GND            |CLK2_BIDIR_N   |GBTCLK4_M2C_N  |GND        |GND        |DP22_C2M_N         |
|6 |DP2_M2C_P   |GND            |DP0_M2C_P  |GND            |HA05_P     |GND        |LA00_P_CC  |GND        |HA03_P         |GND            |GND            |DP22_M2C_P |DP21_C2M_P |GND                |
|7 |DP2_M2C_N   |GND            |DP0_M2C_N  |GND            |HA05_N     |HA04_P     |LA00_N_CC  |LA02_P     |HA03_N         |HA02_P         |GND            |DP22_M2C_N |DP21_C2M_N |GND                |
|8 |GND         |DP8_M2C_P      |GND        |LA01_P_CC      |GND        |HA04_N     |GND        |LA02_N     |GND            |HA02_N         |GBTCLK3_M2C_P  |GND        |GND        |DP20_C2M_P         |
|9 |GND         |DP8_M2C_N      |GND        |LA01_N_CC      |HA09_P     |GND        |LA03_P     |GND        |HA07_P         |GND            |GBTCLK3_M2C_N  |GND        |GND        |DP20_C2M_N         |
|10|DP3_M2C_P   |GND            |LA06_P     |GND            |HA09_N     |HA08_P     |LA03_N     |LA04_P     |HA07_N         |HA06_P         |GND            |DP21_M2C_P |DP10_M2C_P |GND                |
|11|DP3_M2C_N   |GND            |LA06_N     |LA05_P         |GND        |HA08_N     |GND        |LA04_N     |GND            |HA06_N         |GND            |DP21_M2C_N |DP10_M2C_N |GND                |
|12|GND         |DP7_M2C_P      |GND        |LA05_N         |HA13_P     |GND        |LA08_P     |GND        |HA11_P         |GND            |GBTCLK2_M2C_P  |GND        |GND        |DP11_M2C_P         |
|13|GND         |DP7_M2C_N      |GND        |GND            |HA13_N     |HA12_P     |LA08_N     |LA07_P     |HA11_N         |HA10_P         |GBTCLK2_M2C_N  |GND        |GND        |DP11_M2C_N         |
|14|DP4_M2C_P   |GND            |LA10_P     |LA09_P         |GND        |HA12_N     |GND        |LA07_N     |GND            |HA10_N         |GND            |DP20_M2C_P |DP12_M2C_P |GND                |
|15|DP4_M2C_N   |GND            |LA10_N     |LA09_N         |HA16_P     |GND        |LA12_P     |GND        |HA14_P         |GND            |GND            |DP20_M2C_N |DP12_M2C_N |GND                |
|16|GND         |DP6_M2C_P      |GND        |GND            |HA16_N     |HA15_P     |LA12_N     |LA11_P     |HA14_N         |HA17_P_CC      |SYNC_C2M_P     |GND        |GND        |DP13_M2C_P         |
|17|GND         |DP6_M2C_N      |GND        |LA13_P         |GND        |HA15_N     |GND        |LA11_N     |GND            |HA17_N_CC      |SYNC_C2M_N     |GND        |GND        |DP13_M2C_N         |
|18|DP5_M2C_P   |GND            |LA14_P     |LA13_N         |HA20_P     |GND        |LA16_P     |GND        |HA18_P         |GND            |GND            |DP14_C2M_P |DP14_M2C_P |GND                |
|19|DP5_M2C_N   |GND            |LA14_N     |GND            |HA20_N     |HA19_P     |LA16_N     |LA15_P     |HA18_N         |HA21_P         |GND            |DP14_C2M_N |DP14_M2C_N |GND                |
|20|GND         |GBTCLK1_M2C_P  |GND        |LA17_P_CC      |GND        |HA19_N     |GND        |LA15_N     |GND            |HA21_N         |REFCLK_C2M_P   |GND        |GND        |GBTCLK5_M2C_P      |
|21|GND         |GBTCLK1_M2C_N  |GND        |LA17_N_CC      |HB03_P     |GND        |LA20_P     |GND        |HA22_P         |GND            |REFCLK_C2M_N   |GND        |GND        |GBTCLK5_M2C_N      |
|22|DP1_C2M_P   |GND            |LA18_P_CC  |GND            |HB03_N     |HB02_P     |LA20_N     |LA19_P     |HA22_N         |HA23_P         |GND            |DP15_C2M_P |DP15_M2C_P |GND                |
|23|DP1_C2M_N   |GND            |LA18_N_CC  |LA23_P         |GND        |HB02_N     |GND        |LA19_N     |GND            |HA23_N         |GND            |DP15_C2M_N |DP15_M2C_N |GND                |
|24|GND         |DP9_C2M_P      |GND        |LA23_N         |HB05_P     |GND        |LA22_P     |GND        |HB01_P         |GND            |REFCLK_M2C_P   |GND        |GND        |DP10_C2M_P         |
|25|GND         |DP9_C2M_N      |GND        |GND            |HB05_N     |HB04_P     |LA22_N     |LA21_P     |HB01_N         |HB00_P_CC      |REFCLK_M2C_N   |GND        |GND        |DP10_C2M_N         |
|26|DP2_C2M_P   |GND            |LA27_P     |LA26_P         |GND        |HB04_N     |GND        |LA21_N     |GND            |HB00_N_CC      |GND            |DP16_C2M_P |DP11_M2C_P |GND                |
|27|DP2_C2M_N   |GND            |LA27_N     |LA26_N         |HB09_P     |GND        |LA25_P     |GND        |HB07_P         |GND            |GND            |DP16_C2M_N |DP11_M2C_N |GND                |
|28|GND         |DP8_C2M_P      |GND        |GND            |HB09_N     |HB08_P     |LA25_N     |LA24_P     |HB07_N         |HB06_P_CC      |SYNC_M2C_P     |GND        |GND        |DP12_C2M_P         |
|29|GND         |DP8_C2M_N      |GND        |TCK            |GND        |HB08_N     |GND        |LA24_N     |GND            |HB06_N_CC      |SYNC_M2C_N     |GND        |GND        |DP12_C2M_N         |
|30|DP3_C2M_P   |GND            |SCL        |TDI            |HB13_P     |GND        |LA29_P     |GND        |HB11_P         |GND            |GND            |DP17_C2M_P |DP13_M2C_P |GND                |
|31|DP3_C2M_N   |GND            |SDA        |TDO            |HB13_N     |HB12_P     |LA29_N     |LA28_P     |HB11_N         |HB10_P         |GND            |DP17_C2M_N |DP13_M2C_N |GND                |
|32|GND         |DP7_C2M_P      |GND        |3P3VAUX        |GND        |HB12_N     |GND        |LA28_N     |GND            |HB10_N         |RES2           |GND        |GND        |DP16_M2C_P         |
|33|GND         |DP7_C2M_N      |GND        |TMS            |HB19_P     |GND        |LA31_P     |GND        |HB15_P         |GND            |RES3           |GND        |GND        |DP16_M2C_N         |
|34|DP4_C2M_P   |GND            |GA0        |TRST_L         |HB19_N     |HB16_P     |LA31_N     |LA30_P     |HB15_N         |HB14_P         |GND            |DP18_C2M_P |DP17_M2C_P |GND                |
|35|DP4_C2M_N   |GND            |12P0V      |GA1            |GND        |HB16_N     |GND        |LA30_N     |GND            |HB14_N         |GND            |DP18_C2M_N |DP17_M2C_N |GND                |
|36|GND         |DP6_C2M_P      |GND        |3P3V           |HB21_P     |GND        |LA33_P     |GND        |HB18_P         |GND            |12P0V          |GND        |GND        |DP18_M2C_P         |
|37|GND         |DP6_C2M_N      |12P0V      |GND            |HB21_N     |HB20_P     |LA33_N     |LA32_P     |HB18_N         |HB17_P_CC      |12P0V          |GND        |GND        |DP18_M2C_N         |
|38|DP5_C2M_P   |GND            |GND        |3P3V           |GND        |HB20_N     |GND        |LA32_N     |GND            |HB17_N_CC      |GND            |DP19_C2M_P |DP19_M2C_P |GND                |
|39|DP5_C2M_N   |GND            |3P3V       |GND            |VADJ       |GND        |VADJ       |GND        |VIO_B_M2C      |GND            |GND            |DP19_C2M_N |DP19_M2C_N |GND                |
|40|GND         |RES0           |GND        |3P3V           |GND        |VADJ       |GND        |VADJ       |GND            |VIO_B_M2C      |12P0V          |GND        |GND        |3P3V               |


# FMC+ (HPSCe)
|Column\row|A       |B              |C              |D                  |
|-  |-              |-              |-              |-                  |
|1  |GND            |GBTCLK1_M2C_P  |GND            |HSPCE_PRSNT_M2C_L  |
|2  |GND            |GBTCLK1_M2C_N  |GND            |RES6               |
|3  |DP24_C2M_P     |GND            |DP24_M2C_P     |GND                |
|4  |DP24_C2M_N     |GND            |DP24_M2C_N     |GND                |
|5  |GND            |DP25_C2M_P     |GND            |DP25_M2C_P         |
|6  |GND            |DP25_C2M_N     |GND            |DP25_M2C_N         |
|7  |DP26_C2M_P     |GND            |DP26_M2C_P     |GND                |
|8  |DP26_C2M_N     |GND            |DP26_M2C_N     |GND                |
|9  |GND            |DP27_C2M_P     |GND            |DP27_M2C_P         |
|10 |GND            |DP27_C2M_N     |GND            |DP27_M2C_N         |
|11 |DP28_C2M_P     |GND            |DP28_M2C_P     |GND                |
|12 |DP28_C2M_N     |GND            |DP28_M2C_N     |GND                |
|13 |GND            |DP29_C2M_P     |GND            |DP29_M2C_P         |
|14 |GND            |DP29_C2M_N     |GND            |DP29_M2C_N         |
|15 |DP30_C2M_P     |GND            |DP30_M2C_P     |GND                |
|16 |DP30_C2M_N     |GND            |DP30_M2C_N     |GND                |
|17 |GND            |DP31_C2M_P     |GND            |DP31_M2C_P         |
|18 |GND            |DP31_C2M_N     |GND            |DP31_M2C_N         |
|19 |RES4           |GND            |GBTCLK7_M2C_P  |GND                |
|20 |RES5           |GND            |GBTCLK7_M2C_N  |GND                |




# [XILINX XDC Templates](/FMC_xdc/)