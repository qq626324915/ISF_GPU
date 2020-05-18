Title of the manuscript: A fast method for calculation of marine gravity anomaly.

Name of the program: ISF_GPU.m.

Author details: Yuan Fang, Jun Wang, Xiaohong Meng, Yongkang Gan, Hanhan Tang.
                School of Geophysics and Information Technology, China University
                of Geosciences, Beijing 100083, China.

Emails: fangyuan_cugb@foxmail.com;
	wangjun5505@163.com(Jun Wang);
	mxh@cugb.edu.cn(Xiaohong Meng);
	gy_kavin809@126.com(Yongkang Gan);
	3010180015@cugb.edu.cn(Hanhan Tang).
 
 
Description:
  This code is implementation of the Inverse Stokes Formula method, in which the calculation process is improved and GPU parallel computing is incorporated. Marine gravity anomalies can be inverted from the geoid height undulation via this code. Two subfunctions are included in this code: 1) function [dat, nx, ny, xmin, xmax, ymin, ymax]= Grdread( filename) is used to read the gridded data; 2) Grdwrite( dat, filename, nx, ny, xmin, xmax, ymin, ymax) is used to write the gridded data.
