LANGKAH – LANGKAH MEMBUAT REPOSITORY LOKAL DAN REPOSITORY PADA GITHUB DAN MEMBUAT FILE README.md
Yang dibutuhkan :
1.	Akun github
2.	Software git

Langkah membuat akun Repository :

1.	Buat akun git di laman https://github.com , masukan Username, Email dan password lalu klik sign up, Lalu Verifikasi akun dengan memasukan chapta
![git15b](https://user-images.githubusercontent.com/57025775/67614244-b0f51780-f7e3-11e9-97bb-a042c44e6431.jpg)

2.Lalu pilih free $0 USD
![git16](https://user-images.githubusercontent.com/57025775/67614261-e7cb2d80-f7e3-11e9-90c8-25631b61a0eb.jpg)

3.	pilih "A LITTLE " dan klik complete setup atau bisa di skip
![git17](https://user-images.githubusercontent.com/57025775/67614286-91122380-f7e4-11e9-8551-4933c623b56c.jpg)

4.	cek di gmail anda akan ada pesan baru dari github dan klik verfiy email address
![git18](https://user-images.githubusercontent.com/57025775/67614301-e2221780-f7e4-11e9-9262-06215da533d1.jpg)

5.	lalu akan di alihkan ke tab baru untuk create a new repository isi repository name lalu klik create repository
![git19c](https://user-images.githubusercontent.com/57025775/67614311-139ae300-f7e5-11e9-889a-dcd89e8767f3.jpg)

6.	tampilan repository yang baru
![git20](https://user-images.githubusercontent.com/57025775/67614320-4644db80-f7e5-11e9-87df-aad6984d911a.jpg)

Menginstall aplikasi git :

Download software git di “git-scm.com” dan install software git terlebih dahulu untuk anda pengguna windows, berikut ini cara menginstall git di windows.

1.	Download git versi windows terbaru.  Selesai di download , klik kanan aplikasi git yang akan diinstall lalu pilih/klik “Run as administrator”.

![git 1](https://user-images.githubusercontent.com/57025775/67614332-7be9c480-f7e5-11e9-8044-495f98cb3a77.jpg)

2.	Setelah di Run maka akan muncul tampilan mengenai license seperti dibawah ini, lalu klik next

![git 2](https://user-images.githubusercontent.com/57025775/67614338-a176ce00-f7e5-11e9-8954-95a5eadfb18e.jpg)

3.	Setelah di klik maka akan muncul pilihan komponen yang akan di install seperti di bawah ini, lalu klik next

![git 4](https://user-images.githubusercontent.com/57025775/67614354-d97e1100-f7e5-11e9-8cba-ab2fb75a62bd.jpg)

4.	Selanjutnya pilih editor untuk menggunakan git nantinya, klik next

![git 5](https://user-images.githubusercontent.com/57025775/67614362-fc102a00-f7e5-11e9-89f0-3abfc7d749b6.jpg)

5.	Setelah next akan muncul tampilan mengatur path environment , pilih “use git from the windows command prompt”, lalu klik next

![git 6](https://user-images.githubusercontent.com/57025775/67614368-1a762580-f7e6-11e9-922f-5b8b242b2461.jpg)

6.	Selanjutnya memilih jenis koneksi ke server , pilih “use the openSSL library”, lalau klik next

![git 7](https://user-images.githubusercontent.com/57025775/67614380-45f91000-f7e6-11e9-84d8-3788b97d43e9.jpg)

7.	Selanjutnya mengatur baris akhir file teks nantinya , pilih “checkout windows-style, commit unix-style line endings” , lalu klik next

![git 8](https://user-images.githubusercontent.com/57025775/67614385-6032ee00-f7e6-11e9-94ec-98155b48a3b2.jpg)

8.	Selanjutnya mengatur terminal emulator yang akan digunakan dg git bash, pilih “ use minTTY (the default terminal of MSYS2)” , lalu klik next

![git 9](https://user-images.githubusercontent.com/57025775/67614391-8062ad00-f7e6-11e9-927b-e653594acfee.jpg)

9.	Selanjutnya memilih opsi tambahan yang mungkin diperlukan, pilih “enable file system caching “ dan “enable git credential manager”, lalu klik next

![git 10](https://user-images.githubusercontent.com/57025775/67614399-a8521080-f7e6-11e9-8f49-0d15977cb783.jpg)

10.	Selanjutnya pilih install 

![git 11](https://user-images.githubusercontent.com/57025775/67614416-d899af00-f7e6-11e9-8dd3-06b5c82956d2.jpg)

11.	Proses pengistalan akan dijalankan, tunggu hingga proses selesai 100%
![git 12](https://user-images.githubusercontent.com/57025775/67614420-ef400600-f7e6-11e9-8972-850785713cc0.jpg)

12.	Proses instalasi git di windows selesai.
![git 13](https://user-images.githubusercontent.com/57025775/67614424-054dc680-f7e7-11e9-9ce0-6820956dda84.jpg)

MEMBUAT REPOSITORY LOKAL DAN REPOSITORY PADA GITHUB

Sebelum ke langkah membuat repository Cek apakah Git sudah bisa digunakan akan belum dengan cara membuka Command Prompt dan ketik git --version, jika muncul versi Git maka proses yang dilakukan sudah berjalan dengan baik dan Git siap untuk digunakan.

![git21](https://user-images.githubusercontent.com/57025775/67614470-b8b6bb00-f7e7-11e9-9d74-724128014237.jpg)

1.	lalu buka document dan buat folder baru klik kanan pada folder lalu pilih ” git bash here “

![git22](https://user-images.githubusercontent.com/57025775/67614494-10552680-f7e8-11e9-82ae-4ef5dda90d19.jpg)

2.	lalu konfigurasi dengan memasukan perintah " git config --global user.name “nama_user” " dan " git config --global user.email “nama_user”

![git23](https://user-images.githubusercontent.com/57025775/67614542-1697d280-f7e9-11e9-832a-33d9d632ccf8.jpg)

3.	buat direktori baru dengan menggunakan perintah " mkdir latihan1" lalu " cd latihan1 "

![git24](https://user-images.githubusercontent.com/57025775/67614549-421abd00-f7e9-11e9-858c-41da6f821f49.jpg)

4.	jalan kan perintah " git init " untuk membuat file kosong berformat .git

![git25](https://user-images.githubusercontent.com/57025775/67614570-74c4b580-f7e9-11e9-8001-551e3463f004.jpg)

5.	lalu buat 1 file bernama readme.md dengan memasukan perintah " echo "#latihan1" >> readme.md “ lalu ketikan perintah " ls -l " untuk melihat file

![git26](https://user-images.githubusercontent.com/57025775/67614589-c10ff580-f7e9-11e9-9069-9aa1edb5c048.jpg)

6.	menambahkan file readme. md pada repository local dengan menggunakan perintah " git add "

![git28](https://user-images.githubusercontent.com/57025775/67614614-3a0f4d00-f7ea-11e9-8c34-a8c34bdee7fd.jpg)

7.	ketik perintah " git commit -m " komentar saya " untuk menyimpan perubahan yang ada ke dalam database repository

![git30](https://user-images.githubusercontent.com/57025775/67614625-6dea7280-f7ea-11e9-9c0d-ef0cf2e551a3.jpg)

8.	masuk lagi ke website github lalu masuk ke repositori yang sebelum nya di buat.
pada bagian quick setup terdapat url github kita... url ini nantinya akan di gunakan menggunakan perintah “git remote add origin [url] “ dan perintah git clone “ git clone [ url ] “

![git31](https://user-images.githubusercontent.com/57025775/67614641-e3eed980-f7ea-11e9-88e8-f0ded22bc6b0.jpg)

9.	lalu ketikan perintah " git remote add origin [url] " contoh " git remote add origin https://github.com/khusnanz/Latihan1.git  "

![git32](https://user-images.githubusercontent.com/57025775/67614648-0d0f6a00-f7eb-11e9-8250-2b02ad50a609.jpg)

10.	untuk mengirim perubahan local repository ke server gunakan perintah git push " git push -u origin master

![git33](https://user-images.githubusercontent.com/57025775/67614679-5bbd0400-f7eb-11e9-9a3a-5b2042e50865.jpg)

11.	 untuk melihat hasil nya cek di github dan lihat di repository-nya

![git34](https://user-images.githubusercontent.com/57025775/67614691-97f06480-f7eb-11e9-815e-1cd8ecc2ba27.jpg)


12.	langkah – langkah membuat repository lokal dan repository pada github dan membuat file readme.md selesai
![git35](https://user-images.githubusercontent.com/57025775/67614714-f289c080-f7eb-11e9-86ee-d519a15a31a4.jpg)



Demikian penjelasan mengenai langkah – langkah membuat repository lokal dan repository pada github dan membuat file readme.md. Semoga bermanfaat  

