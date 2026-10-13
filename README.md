Tugas 6


Eksekusi seluruh profile yang ada :

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”

<img width="498" height="186" alt="image" src="https://github.com/user-attachments/assets/0c6926d5-08f9-454e-8d68-d4688a5532c5" />


b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/4f244d77-eb69-495f-b890-a8282d41c689" />

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : echo “Profile dari .bash_profile” Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.


c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/dfc6d412-f11b-4df9-ad09-6bb3fab2cae9" />



Prompt String (PS)
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell


<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/7da3c318-7ede-4ffc-b69a-7d5e9e24f9c3" />


b. Eksperimen hasil PS1 :

2a
Logout
3 tugas 6
Bash script a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : p1.sh #! /bin/bash
4 a 1
p2.sh #! /bin/bash

4 a 2
p3.sh #! /bin/bash

4 a 3
b. Jalankan script tersebut sebagai berikut : 4b1

4b2 42b3 4b4
Jobs a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
5 tugas 6
b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :

5b
c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background

5c
d. Stop program background dengan utilitas kill

5d
History a. Ganti nilai HISTSIZE dari 1000 menjadi 20
6a1
b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan

6b
c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer

6c
d. Ulangi instruksi pada history bufer nomor 150

6d
e. Ulangi instruksi dengan prefix “ls”

6e
