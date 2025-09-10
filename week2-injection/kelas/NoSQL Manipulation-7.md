# 1. NoSQL Manipulation-7

# 2. https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false

# 3. Penyelesaian

a. Kita disuruh untuk memanipulasi semua product review sekaligus caranya adalah dengan memodifikasi parameter yang ada di endpoint /rest/products/reviews
  kemudian karena request default-nya pakai PUT, untuk bisa update review kita harus ganti metodenya jadi PATCH. Lalu, di bagian parameter author kita ganti jadi ProductId. Nilainya kita set supaya tidak sama dengan -1. ```{"$ne":-1}```

- Ganti ke patch
  
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6941516d-5e2c-42c9-a892-3b812dc02afa" />

- gunakan payload
- 
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2d80f3d3-83a5-425c-8ea9-a2863fd74f3a" />
