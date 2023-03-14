# Comparison-of-Filter-Wrapper-and-Embedded-Feature-Selection-Methods-with-9-Different-Models-on-Man
This repository contains the code, data, and documentation of the project that me and my friend did. This project is about Feature Selection Method on NIRS Mango Dataset that contains thousand of wavelength of NIRS experiment on mango fruit.
Folder ini berisi beberapa file kode seleksi fitur beserta klasifikasi data NIRS mangga (https://data.mendeley.com/datasets/b9d6s7hr33/1) dalam eksteksi Jupyter Notebook (.ipynb). Sebelum menjalankan files kode ini, harap sesuaikan path pemanggilan dataset NIRS mangga. File dataset NIRS mangga berjudul "nirsMangga.csv". 

Alur kode pada setiap file umumnya adalah: 
1. Import Libraries yang dibutuhkan (harap menginstall libraries yang belum di install)
2. Import  dan split Dataset 
3. Proses Seleksi Fitur
4. Proses Klasifikasi dan pengujian model yang dibangun menggunakan fitur-fitur hasil seleksi fitur

Terdapat 9 file kode seleksi fitur beserta klasifikasinya. Kesembilan seleksi fitur ini yaitu ANOVA, Mutual Information, FIsher Score, ReliefF, Forward Selection, Backward Elimination, Recursive Feature Elimination, Elastic Net, dan LASSO. Selain itu terdapat juga file untuk melihat EDA dan fitur fitur terbaik.

Untuk menjalankannya, jalankan setiap cell secara berurutan.
