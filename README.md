# Tugas1_ADJ_191402039
- Setelah siap membuat file html yang ingin di publish, buat satu direktori dan masukkan file html tesebut: 
![WhatsApp Image 2021-09-06 at 23 07 34](https://user-images.githubusercontent.com/62231015/132715441-0180520b-2963-49de-bfa4-f142c82b0147.jpeg)
Kemudian tambahkan file docker dan tambahkan kode berikut
![WhatsApp Image 2021-09-06 at 23 08 08](https://user-images.githubusercontent.com/62231015/132716033-0b335fb1-89c2-43be-95c8-54eb1053d559.jpeg)
![WhatsApp Image 2021-09-06 at 23 07 57](https://user-images.githubusercontent.com/62231015/132716288-48609a28-eb40-46b2-ab8c-98b44fa23ca1.jpeg)
Kemudian build image docker dengan menambahkan command berikut:
![WhatsApp Image 2021-09-06 at 23 09 09](https://user-images.githubusercontent.com/62231015/132716455-e8f2a36a-66e8-4751-81e9-9644342b75e8.jpeg)
Kemudian untuk mengkonfirmasi ketikkan docker images :
![WhatsApp Image 2021-09-06 at 23 09 31](https://user-images.githubusercontent.com/62231015/132716467-4bf9ad94-b186-4374-bac0-dd969f473112.jpeg)
Run file html nya container ketikkan command docker run -d -p 80:80 html-server-image:v1 : dan hasilnya seperti berikut

