# MultiTracerBAORSD

Here are the DR16 BAO and RSD measurements and covariance matrix in Wang et al 2020 (https://arxiv.org/abs/2007.09010).

# sdss_DR16_MultiTracerELGLRG_FS_xi.dat :
The best-fit values with 1\sigma error bars for the parameters (DM/rd, DH/rd, f\sigma_8)

and 

# sdss_DR16_MultiTracerELGLRG_FS_xi_cov.dat :
The covariance matrix between (DM/rd, DH/rd, f\sigma_8)

Note that this measurement can be used together with the BAO&RSD measurements in the first six redshift bins, ie (0.2<z<0.59) from BOSS DR12 (https://arxiv.org/abs/1709.05173 or https://github.com/ytcosmo/TomoBAORSD), or together with BAO peak meaurements alone within 0.2<z<0.59 from BOSS DR12 in Wang et al 2016 (https://arxiv.org/abs/1607.03154 or https://github.com/ytcosmo/TomoPost-BAO). The meassurements at redshifts larger than 0.6 from BOSS DR12 are eliminited, because BOSS DR12 galaxies in the redshift range of 0.6<z<1.0 are included in the DR16 LRG sample. 

Here are the correlation function multipoles and covariance matrices in Wang et al 2020 (https://arxiv.org/abs/2007.09010).

# xi024_ELG_NGC_woAngSys_zRP0p845_cut30.dat and xi024_ELG_SGC_woAngSys_zRP0p845_cut30.dat :

The autocorrelation function multipoles (s, xi0, xi2, xi4) from eBOSS DR16 ELG sample in NGC and SGC, where the angular systematics have been corrected. 

# xil_All_eBOSS_cross_clustering_NGC_v7.txt and xil_All_eBOSS_cross_clustering_SGC_v7.txt:

The cross-correlation function multipoles (s, xi0, xi2, xi4) from cross sample in NGC and SGC. 

# xil_all_eBOSS_LRGpCMASS_clustering_NGC_v7.txt and xil_all_eBOSS_LRGpCMASS_clustering_SGC_v7.txt:

The autocorrelation function multipoles (s, xi0, xi2, xi4) from eBOSS DR16 LRG sample and BOSS DR12 CMASS sample within $0.6<z<1.0$ in NGC and SGC. 

# The Radial integral constraint
The RIC effects for different samples are estimated from mocks, which are subtracted from the data measurements above.
ELG sample: New_ELG_NGC_RIC_xi024.dat and New_ELG_SGC_RIC_xi024.dat in the format of (s, xi0, xi2, xi4)
CROSS sample: CROSS_NGC_RIC_xi024.dat and CROSS_SGC_RIC_xi024.dat in the format of (s, xi0, xi2, xi4)
LRGpCMASS sample: LRGpCMASS_NGC_RIC_xi024.dat and LRGpCMASS_SGC_RIC_xi024.dat in the format of (s, xi0, xi2, xi4)

# All_woangsys_cut30_0p845_womeanRIC_NGC_covmat.dat_corrected_xi024_smin30 and All_woangsys_cut30_0p845_womeanRIC_SGC_covmat.dat_corrected_xi024_smin30 :

Covariance matrices (216x216) for ELG xi multipoles (xi0, xi2, xi4), CROSS xi multipoles (xi0, xi2, xi4), and LRGpCMASS xi multipoles (xi0, xi2, xi4). For each sample, we have 72 data points, ie xi multipoles (xi0, xi2, xi4) in the range 30<s<150 Mpc/h with a bin width of 5 Mpc/h.

# MultiTracerBAORSD
