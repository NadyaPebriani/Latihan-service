# Membuat Microservice Sederhana

# About
Menngunakan Maven Spring
<br>Menggunakan Spriring Boot versi 2.6.11
<br>Menngunakan Apache Netbeans IDE 13
<br>Menggunakan Bahasa Java
<br>Menggunakan JDK 17
<br>Menggunakan Microsoft Edge

## Donwload Project Maven
**Langkah 1 :** Buat Project Maven menggunakan spring Inirializr https://start.spring.io/
<br>**Langkah 2 :** pilih Maven project pada pilihan project, pilih bahasa java
<br>**Langkah 3 :** pilih springBoot versi 2.6.11 M6 atau versi yang lebih tinggi. Jangan memilih versi snapshot
<br>**Langkah 4 :** Berikan nama group pada project maven yang telah dibuat yaitu com.nadya
<br>**Langkah 5 :** Berikan id Artefak pada project yaitu latihan-service dan secara otomatis akan mengisi bagian name
<br>**Langkah 6 :** Tambahkan description untuk project yang akan kita buat
<br>**Langkah 7 :** Pilih java atau jdk 17,pastikan sesuai dengan jdk yang tealah kita instals
<br>**Langkah 8 :** Tambahkan dependensi yaitu hanya spring wweb saja
<br>**Langkah 9 :** Lalu kita geberate the project, file zip akan diunduh, setelah itu ekstrak file copekan file ke D,saya menyimpan file di D.
<br>**Langkah 10 :** Jalankan netbeans lalu import project yang telah kita ekstract tadi.Butuh beberapa waktu untuk mengunduh file yang diperlukan
<br>**Langkah 11 :** Lalu build and dependecies pada project yang sudah kita import
<br>**Langkah 12 :** Jalankan LimitServiceAplication, memulai tomcat pada port (s) 8010 (http)

## Proyek Spring Boot
**Langkah 1 :**
<br>Menggunakan mulai.spring.io untuk membuat proyek "web".Dalam dialog "dependenciens" cari dan tambahkan Dependencies ke layar. Tekan tombol "Hasilkan", unduh zip, dan buka kemasannya ke dalam folder di komputer Anda.![image](https://user-images.githubusercontent.com/113502682/192440034-0177bb4d-e86d-411a-b3cd-7c1cfcbaab4c.png)
**Langkah 2 :**
<br>Buka proyek di IDE Anda dan cari DemoApplication.javafile di src/main/java/com/example/demofolder. Sekarang ubah isi file dengan menambahkan metode tambahan dan anotasi yang ditunjukkan pada kode di bawah ini.![image](https://user-images.githubusercontent.com/113502682/192440486-13719d21-b699-4f16-af17-579aa134bee0.png)

**Langkah 3 :**
<br>Beberapa baris terakhir di sini memberi tahu kami bahwa Musim Semi telah dimulai. Server Apache Tomcat tertanam pada Spring Boot bertindak sebagai server web dan mendengarkan permintaan pada localhostport 8080. Buka browser Anda dan di bilah alamat di bagian atas enterhttp://localhost:8080/halo. Anda harus mendapatkan respons ramah yang bagus seperti ini:![image](https://user-images.githubusercontent.com/113502682/192439065-6332d8ff-db55-4cb4-8468-b06d24f1a13b.png)

