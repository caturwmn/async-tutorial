# Refleksi tutorial async
1.2. Understanding how it works
![Screenshot pertama tutorial 1](screenshot/result_1.png)
Apa yang terjadi adalah bagian main program mendeklarasi sebuah executor async yang disuruh untuk mengeprint howdy dan done, namun sebelum executor sempat di run, bagian main mencapai kode untuk mengeprint hey hey terlebih dahulu sehingga hey hey diprint terlebih dahulu setelah itu executor dijalankan dan melaksanakan tugasnya.