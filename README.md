# lab2web 
1.Membuat Dokumen HTML

![image](https://user-images.githubusercontent.com/101645216/159826283-a890dcf3-bc34-4b79-a540-d48884697676.png)

Hasil pada browser

![image](https://user-images.githubusercontent.com/101645216/159824253-8105be8a-3c77-45a6-bfc0-a8a5e44787db.png)

2.Mendeklarasikan Tampilan Internal CSS

![image](https://user-images.githubusercontent.com/101645216/159824628-6eafa27c-2f3e-4f19-9e7a-37f2bb1c6f0a.png)

pada browser 

![image](https://user-images.githubusercontent.com/101645216/159824755-e09dfb24-43e5-4246-954b-82bc3cfeb439.png)

3.Menambahkan  Hasil  Inline CSS

![image](https://user-images.githubusercontent.com/101645216/159826787-c753ef51-b809-44b3-bcc6-48819c5469e0.png)

Pada Browser 

![image](https://user-images.githubusercontent.com/101645216/159825190-c4069175-665b-4009-adb9-95fa5ffc3462.png)

4.Membuat CSS eksternal 

![image](https://user-images.githubusercontent.com/101645216/159827734-8d3cc9ed-adae-4210-a17d-c3d9f0b063e4.png)

Menyiapkan link css pada tampilan kepala 

![image](https://user-images.githubusercontent.com/101645216/159827814-cf246357-e358-45cd-8017-bc8168f91cfe.png)

tampilan pada browser 

![image](https://user-images.githubusercontent.com/101645216/159825832-23c1d3d3-4eae-4d83-990a-1091ab40c6f9.png)

5.penambahan pada CSS selesctor 

![image](https://user-images.githubusercontent.com/101645216/159827549-ba4a05b0-689f-4887-aff2-69e4a0970a8a.png)

Tampilan Browser 

![image](https://user-images.githubusercontent.com/101645216/159826043-996646e7-a9e5-4ec6-8e61-9fb93c039334.png)

Jawablah pertanyaan praktikum 2 

1.Melakukan eskperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu Pada CSS Cheat Sheet yang di berikan pada file terpisah pada modul ini 
![image](https://user-images.githubusercontent.com/101645216/159832408-4fbcc8fe-fe35-4446-989b-396db770e11f.png)

hasil 
![image](https://user-images.githubusercontent.com/101645216/159832469-22f65b58-1f07-4869-931e-1fa5863e1d44.png)

2.Apa perbedaan pendeklarasian CSS element h1 {...} dengan #intro h1 {...}? berikan penjelasannya! Perbedaannya adalah jika hanya menggunakan h1 maka semua yang ada dalam dokumen akan berubah, namun jika menggunakan #intro h1 yang berubah hanya yang memiliki tag intro tersebut. 3. Jika deklarasi CSS secara internal, maka ditambahkan CSS eksternal dan CSS inline pada elemen yang sama.

3.Jika deklarasi CSS secara internal, maka ditambahkan CSS eksternal dan CSS inline pada elemen yang sama. apakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! jika ketiga CSS mengubah elemen yang sama maka deklarasi tersebut akan mengikuti aturan dimana prioritas CSSnya seperti berikut :
- CSS sebaris
- CSS pemilih ID
- CSS internal
- external CSS Contoh: ini adalah tampilan coding pada html testing dimana terdapat 2 kalimat yang memiliki elemen yang sama yaitu h1:
- terdapat 2 CSS yang merubah warna tect h1
![image](https://user-images.githubusercontent.com/101645216/159833327-7864ffb9-af36-4133-b7f4-b38b87b1618d.png)

Tampilan Browser 

![image](https://user-images.githubusercontent.com/101645216/159833408-219dd370-62ba-4f39-b103-5a7281e38ee1.png)

4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing pemilih tersebut terdapat deklarasi CSS, maka deklarasi yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( p id="paragraf-1" class="text-paragraf" ) semakin spesifik css maka akan semakin tinggi prioritas css tersebut. contoh :

![image](https://user-images.githubusercontent.com/101645216/159835250-469233f8-0e18-4c30-a660-88305d974a55.png)

Di situ bisa dilihat terdapat 2 css yang merujuk ke elemen yang sama tapi 1 merujuk dengan id yang birisi font 100px dan warna aqua sedangkan yang satu lagi merujuk dengan kelas yang berisi font 10px dan warna beige:

![image](https://user-images.githubusercontent.com/101645216/159835631-92725b77-1cac-4165-ba7a-b10b5f69f793.png)



