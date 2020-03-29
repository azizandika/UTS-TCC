# Ujian Tengah Semester Teknologi Cloud Computing

## 1. Pembuatan Akun Dockerhub
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/Screenshot_1.png)
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/Screenshot_2.png)
* pada gambar diatas adalah pembuatan akun dockerhub, dengan memasukan id akun email dan password kemudian sign kemudian masuk ke docker dekstop windwows pc.

## 2. Pengerjaan di dokcerhub
* Setelah melakukan buat akin dockerhub, kemudian dilanjutkan melakukan perpindah direktori dengan mengentikan ``cd dooodle/summer2019`` di cmd.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/01.png)
* Kemudian dilanjtkan dengan mengetikan ``docker build -t azizandika/summer2019`` , untuk melakukan penginstallan build summer2019.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/02.png)
* Kemudian ketikan ``docker ps -a``, untuk digunakan sebagai memunculkan daftar container yang sedang berjalan.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/03.png)
* Kemudian ketikan ``docker run -t azizandika/summer2019`` , untuk digunakan menampilkan image pada build summer2019.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/04.png)
* Kemudian akan muncul gambar / image dri build summer2019, seperti gambar dibawah ini.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/05.png)

## 3. Pembuatan Dockerfile dan Push
* pada tahap ini adalah membuat dockerfile dengan menggunakan visual code
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/06.png)
* Setelah pembuatan Dockerfile selesai dibuat, kemudian dilanjutkan dengan melakukan perintah build dengan pengetikkan perintah ``docker build -t uts_aziz``, setelah proses build selesai kemudian dilanjutkan dengan mengetikkan perintah ``docker run -t uts_aziz`` untuk menjalankan image yang dibuat.
 dilanjutkan dengan mengetikkan perintah docker run -t 175610077 untuk menjalankan image yang dibuat
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/07.png)
* Kemudian ketikan ``docker tags uts_aziz azizandika/uts_aziz`` dan ketikan ``dcoker push azizandika/uts_azizandika``
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/08.png)
* Dan yang terakhir adalah gambar berhasil upload didocker.
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/09.png)
* ![Gambar akun docker](https://github.com/azizandika/UTS-TCC/blob/master/10.png)

