# LTFT-ERP
CONTENTS OF THIS FOLDER 
——————————————

* LTFT.ERP_tutorial.R : A step-by-step implementation of the LTFT-ERP algorithm and the associated procedures described in "A Study of Longitudinal Trends in Time-Frequency                               Transformations of EEG Data during a Learning Experiment" by Boland et al. (2021).

* LTFT.ERP_MTFT.ERP_reshape.R: Function for performing Step 1 and Step 2 of the LTFT-ERP algorithm outlined in Section 2 of "A Study of Longitudinal Trends in Time-Frequency                                      Transformations of EEG Data during a Learning Experiment" by Boland et al. (2021). Specifically, this function filters the ERP waveforms for the                                    specified frequency band, performs the wavelet transformations to obtain the TFT power surfaces, and reshapes the subsequent TFT-surfaces into                                      vectors.

* LTFT.ERP_MDPCA.R: Function for performing step 3 of the LTFT-ERP algorithm in which a data-driven dimension reduction of the TFT power vectors is employed via multidimensional                       principal component analysis (MDPCA). Specifically, this function estimates the trial-specific covariance matrices, the marginal covariance matrix, the leading 
                    eigenvectors, and the resulting MDPCA scores.

* LTFT.ERP_mixedEffectsModel.R: Function for performing step 4 of the LTFT-ERP algorithm in which the longitudinal trends of the MDPCA scores are modeled via a linear mixed                                       effects model.

* LTFT.ERP_simulateTFT.R: Function for simulating data for the LTFT-ERP algorithm  as detailed in section 3.1.

INTRODUCTION
——————————————	
The contents of this folder allow for implementation


REQUIREMENTS
——————————————	

INSTALLATION
——————————————
