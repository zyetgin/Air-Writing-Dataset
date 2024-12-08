# Air Writing Dataset as Matlab file
Air Writing Dataset as Matlab file that contains signal values of air write letters, acquired from IMU motion sensors (gyroscope and accelerometer), and also subject IDs. 

Steps:
   load dataset.mat file in Matlab environment. Dataset covers 3 structure (each is an array): data, letter , user.

   data is an array of matrices where data{i} contains the signal values of the 6 sensors, as a matrice(6xn), for the letter(i) and user(i)


