# sustained_NPQ
repository corresponding to 'Sustained Non-Photochemical Quenching Shapes the Seasonal Pattern of Solar-Induced Fluorescence' within JGR-Biogeosciences

 This source code was used to perform the SIF simulations described in Raczka et al., (2019)  JGR-Biogeosciences.
 The three formulation are CLM-SIF, CLM-SIF-NPQ and CLM-SIF-NPQ-Kr.

**IMPORTANT:   CLM-SIF was designed for general use  (multi-site/regional/global simulations)  -no calibration specific to Niwot Ridge.  CLM-SIF-NPQ and CLM-SIF-NPQ-Kr include  parameterizations specific to Niwot Ridge site simulations, not designed for general use.


Solar induced fluorescence description for each model formulation:

CLM-SIF:  Adopted from Lee et al., (2015), adds the impact of nitrogen limitation on Ja.  Uses Flexas et al., (2002) data to parameterize reversible NPQ.

CLM-SIF-NPQ:  Includes representation of both sustained and reversible NPQ.  Sustained NPQ based upon acclimation model of temperature.   Both sustained and reversible NPQ uses PAM fluorometry observations taken at Hyytiala, Finland, and adopted to Niwot Ridge Colorado.


CLM-SIF-NPQ-Kr:  Similar to above but uses seasonal varying representation of reversible NPQ. 



Note:  This source code based off CESM1.2 release of CLM4.5
URL: https://svn-ccsm-models.cgd.ucar.edu/cesm1/release_tags/cesm1_2_1
Repository Root: https://svn-ccsm-models.cgd.ucar.edu
Repository UUID: fe37f545-8307-0410-aea5-b40df96820b5
Revision: 62904
