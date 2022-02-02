# skilvul-webserver-restfulAPI
  
1. Apa perbedaan antara static web server dan dynamic web server?  

Jawab: Static web server adalah web server yang terdiri atas hardware (komputer) dan software (HTTP server) yang mengembalikan file yang dihosting dengan apa adanya pada browser, sedangkan dynamic web server adalah web server yang terdiri atas web server statis dengan tambahan software - biasanya sebuah server aplikasi dan sebuah database. Web server tipe ini disebut dinamis karena server aplikasi akan memperbarui file yang dihosting ebelum mengirimkan kontennya ke browser melalui server HTTP.  

2. Jelaskan arsitektur static site dan dynamic site 
  
Jawab: Seperti yang dapat dilihat pada gambar di bawah, web server akan mencari halaman yang di request oleh web browser dan mengembalikan page tersebut ke browser yang melakukan request.  
  
![static web](https://user-images.githubusercontent.com/68385532/152095338-bef013b5-cbec-46fd-be13-3f9fbe372ae7.jpg)

      
Sedangkan pada dynamic site, web server akan membuat konten respon secara dinamis hanya ketika dibutuhkan.Pada website dinamis, halaman HTML biasanya dibuat dengan memasukkan data dari database ke dalam placeholder yang terdapat dalam template HTML.  

![dinamic web](https://user-images.githubusercontent.com/68385532/152095327-9de26dde-0dd6-4bd6-907f-535ef627df4f.jpg)  

  
3. Apa saja yang dapat kita buat pada sisi server?  
  
Jawab: 
- Meningkatkan efisiensi memori dan penyampaian informasi
- Kustomisasi user experience
- Kontrol akses terhadap konten yang terdapat dalam website
- Menyimpan informasi session/ state 
- Membuat notifikasi dan melakukan komunikasi dengan user  
- Melakukan analisis data  

4. Mohon jelaskan apa itu RESTful?  
  
Jawab: RESTful merupakan sebutan untuk web service yang menerapkan arsitektur REST. Arsitektur REST sendiri (Representational State Transfer) adalah salah satu gaya arsitektur yang menggunakan pola request-response dalam berinteraksi dan sangat populer digunakan karena pengembangannya yang relatif mudah. Arsitektur REST memisahkan peran client dan server sehingga ketik terjadi perubahan besari di sisi client, sisi server tidak akan terdampak, begitu juga sebaliknya.  

5. Apa saja jenis HTTP verbs yang ada (jelaskan fungsinya masing-masing)  
  
Jawab: 
- GET, mengembalikan resource spesifik atau kumpulan resource yang sesuai dengan permintaan
- POST, membuat resource baru 
- PUT, memperbarui resource spesifik  
- DELETE, menghapus resource spesifik  

6. Apa fungsi dari Response Codes?  
  
Jawab: Fungsi dari response codes adalah untuk menginformasikan client mengenai status keberhasilan dari operasi request yang dikirimkan.