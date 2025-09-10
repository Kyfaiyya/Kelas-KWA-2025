# 1. Database Schema

# 2. https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false

# 3. Penyelesaian

a. Search akan memunculkan produk yang memiliki nama atau description yang sesuai dengan keyword yang dicari

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/14d49f73-d8c3-4263-b60c-f56ae01bb5e4" />

b. Setelah dicek ternyata ada 9 column di database (karena ketika masukin 10 column dia error)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4f8c5892-c6bd-49f4-ad9d-4b2cd245e212" />

c. Gunakan payload ```'))+UNION+SELECT+sql,2,3,4,5,6,7,8,9+FROM+sqlite_master--``` dan berhasil mendapatkan database schemanya

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7b74410a-17b2-4f99-ac65-c7ee4f8ae09b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b4e6344f-7d84-450e-918e-0d1daae89d2c" />
