Membuat Tabel Data Mahasiswa Di POSTGRESQL
Buka SQL Shell (psql)

![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/731b4080-02e7-44a2-ae32-4fb17f0e78cf)


Tekan enter terus menerus hingga sistem meminta password, lalu masukkan password

![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/69dd26ee-cb73-443b-ac6a-2276c39b494d)


Buat database dengan nama "polban" terlebih dahulu 
Masuk ke database polban dengan mengetik "\c polban"
Apabila sudah masuk ke database polban, buat tabel dengan perintah CREATE TABLE  nama tabel (kolom 1 datatype, kolom 2 datatype, begitu seterusnya);
contoh : CREATE TABLE maahasiswa_ (nama varchar(30));
Setelah tabel terbuat, data-data pengisi tabel dapat diinputkan dengan INSERT INTO nama tabel (kolom yang akan diisi) VALUES (data yang diinputkan);

![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/b5cd5084-9276-4e9e-8284-738016c4fb54)


Lakukan secara berulang hingga semua data terinput


![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/9bcdcc0e-3c75-4949-82f5-5020f6713bc4)

![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/e2d60c5c-01ac-4cea-a290-537087494f9a)


Setelah semua data terinput, tabel dapat dilihat dengan mengetik "SELECT * FROM nama tabel"
a. tampilan pada SQL Shell (psql)


![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/cb2c32d2-fd99-41da-9458-1d089a9658b4)



b. tampilan pada PGAdmin 4


![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/c40ed5db-fdd9-4d78-91a9-bc3a8069f4f6)



c. tampilan pada DBeaver


![image](https://github.com/Rezza-Mediani/pertemuan1-basis-data/assets/148309853/34558952-7471-4dbb-9a46-901fffad50e0)


