# installation-des-paquets

# MYSQL
 ```
 cd emplacement_source_mysql
 tar -zxvf mysql-8.3.0.tar.gz
 cd mysql-8.3.0
 ```
 ```
 sudo apt install cmake
 ```
 ```
 mkdir docs
 cd docs
 ```
 ```
 cmake
 ```
 ```
 sudo apt-get upgrade
 ```
 
 ```
 sudo apt-get install libssl-dev
 ````
 ```
 sudo apt-get install openssl
 ```
 ```
 cmake ..
 ```
 
 ```
 sudo make
 ```
 ```
 sudo make install
 ```
<img src="https://github.com/Miah-Sitraka/installation-des-paquets/blob/main/mysql.png" alt="Capture_ecran_mysql" >

# APACHE
```
cd emplacement_source_httpd-2.4.59.tar.gz
tar -zxvf httpd-2.4.59.tar.gz
cd httpd-2.4.59
```
```
./configure
```
```
sudo apt-get install libapr1-dev
```
```
sudo apt-get install libaprutil1-dev
```
```
sudo apt-get install libpcre2-posix2 libpcre2-dev
```
```
./configure
```
```
sudo make
```
```
sudo make install
```
<img src="https://github.com/Miah-Sitraka/installation-des-paquets/blob/main/Capture%20d%E2%80%99%C3%A9cran%20du%202024-04-21%2012-05-26.png" alt="Capture_ecran_apache" >

# PHP
```
cd emplacement_source_php-8.3.6.tar.gz
tar -zxvf php 8.3.6.tar.gz
cd php-8.3.6
```
```
./configure
```
```
sudo apt install pkg-config
```
```
sudo apt install libxml2-dev
```
```
sudo apt install libsqlite3-dev
```
```
./configure
```
```
sudo make
```
```
sudo make install
```
<img src="https://github.com/Miah-Sitraka/installation-des-paquets/blob/main/Capture%20d%E2%80%99%C3%A9cran%20du%202024-04-21%2016-36-17.png" alt="Capture_ecran_php" >

 



