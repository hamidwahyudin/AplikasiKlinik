# AplikasiKlinik
AplikasiKlinik | Mata Kuliah Pemrograman Visual | Java | Semester 6

Langkah instalasi : 
1. Download atau clone repository ini.
2. Buat Database mysql dengan nama klinik
   `CREATE DATABASE klinik`
3. Buat struktur databasenya
    
    id      varchar(30) 
    
    nama    varchar(100)
    
    jk      varchar(20) 
    
    alamat  varchar(200)
    
    goldar  varchar(2)  
    

   atau 

   `
   CREATE TABLE pasien (
    id varchar(30) NOT NULL,
    nama varchar(100) DEFAULT NULL,
    jk varchar(20) DEFAULT NULL,
    alamat varchar(200) DEFAULT NULL,
    goldar varchar(2) DEFAULT NULL,
    PRIMARY KEY (id)
   ) DEFAULT CHARSET=latin1
   `
