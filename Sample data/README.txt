FeatureMat_timeWin:
FFT power values extracted for three frequency bands (theta, alpha, beta). 
Features are arranged in band and electrodes order (theta_1, theta_2..., 
theta_19, alpha_1, alpha_2, ..., beta_19). There are 4 time windows, 
features for each time window are aggregated sequentially 
(i.e. 0:56 --> time window 1, 57:113 --> time windw 2 and so on. Last 
column contains the class labels (load levels).

locations:
3 dimensional Cartesian coordinates for electrodes (x, y, z).

trials_subNums:
contains subject numbers associated with each trial (used for leave-subject-out
 cross validation).

To see separated subjects data use FeatureMat_timeWin33.mat, trials_subNums34.mat
 and so on (33, 34 - just id numbers of subjects).
 
To see raw data go to rawData.

P.S.
This sample data differs from data, described in the original repository
https://github.com/pbashivan/EEGLearn.

