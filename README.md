# Air-Writing-Dataset as Matlab file
Air-Writing Dataset as Matlab file that contains signal values of air write letters, acquired from IMU motion sensors (gyroscope and accelerometer), and also subject IDs. 

Steps:
1) load dataset.mat file in Matlab environment. Dataset covers 3 structure (each is an array): data, letter , user.

   data is an array of matrices where data{i} contains the signal values of the 6 sensors, as a matrice(6xn), for the letter(i) and user(i)

2) Please cite the following papers in order to use the dataset.
   
Ecer, O., Yetgin, Z., & Çelik, T. (2018). Air Write Letter Recognition Using Random Forest Classification on Arduino Dataset. International Journal of Scientific and Technological Research, 4, 1-9.
