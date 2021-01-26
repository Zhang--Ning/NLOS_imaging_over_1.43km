# NLOS_imaging_over_1.43km

This demo includes data and MATLAB codes used in the paper "Non-line-of-sight imaging over 1.43 kilometers" by Cheng Wu, Jianjiang Liu, Xin Huang, Zheng-Ping Li, Chao Yu, Jun-Tian Ye, Jun Zhang, Qiang Zhang, Xiankang Dou, Vivek K. Goyal, Feihu Xu, and Jian-Wei Pan (to appear in PNAS(2021)).

Corresponding author: feihuxu@ustc.edu.cn.

To try the codes, just download the zip and run the "demo_12_08_2020.m" in MATLAB. Warning: the code was tested using MATLAB 2018a and 2018b, it might be incompatible with older versions.

Attribution

Data

The experimental lidar data is obtained by our new single-photon lidar system, including a letter 'H.mat' and a mannequin 'mannequin.mat'.
Instructions for the experimental data:

'data_processed': (type: 64 \times 64 \times 512 double), it contains the temporal distribution(histogram) of arrival photons at each pixel.
'timeResolution': (type: double), it represents the time resolution of the time-digital-convertet(TDC) (unit:s)
'pulsewidth': (type: double), it represents the pulse width of the histogram in 'data_processed' (unit:s)
'width': (type: double), it represents the width of scanning area

Code

Our algorithm is based on following two papers:

O’Toole, Matthew, David B. Lindell, and Gordon Wetzstein. "Confocal non-line-of-sight imaging based on the light-cone transform." Nature 555.7696 (2018): 338-341.

Harmany, Zachary T., Roummel F. Marcia, and Rebecca M. Willett. "This is SPIRAL-TAP: Sparse Poisson intensity reconstruction algorithms—theory and practice." IEEE Transactions on Image Processing 21.3 (2011): 1084-1096.