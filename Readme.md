run Ubuntu 20 แล้วติดตั้ง Application apache2 และ Git แล้วทำการ pull หรือ clone ตัว repository จาก GitHub ของตนเองมา run
เริ่มต้นด้วยการสมัคร github และสร้าง repository Sync กับไฟล์บน Visual Studio code ไฟล์ index.html เป็นไฟล์หน้าเว็บอย่างง่ายที่จะแสดงชื่อ นามสกุล และรหัสประจำตัวนักศึกษา
![image](https://github.com/Pariwattt/CE341_ID2019/assets/149044545/29eeac36-6767-444f-9eea-14b1a806c703)
เปิด Ubuntu แล้วติดตั้ง Application apache2 และ Git และให้หา ip ของเราด้วยคำสั่ง ip a แล้วนำ ip ของเราไปใส่ใน Web browser 
![image](https://github.com/Pariwattt/CE341_ID2019/assets/149044545/7194f1bb-d932-4a16-9928-e5d017ae187d)
![test2](https://github.com/Pariwattt/CE341_ID2019/assets/149044545/7f1a233c-da77-4c9d-9dc3-c9f0658fd83d)
ถ้าไม่ได้หน้านี้ต้องทำการ start หรือ restart apache2 ก่อน
ต่อไปเราก็ทำการนำ file เว็บที่เราทำ มา replace ที่ /var/www/html/index.html โดย sudo mv index.html /var/www/html.index
และทำการรีหน้าเว็บของเรา และจะได้
![test5](https://github.com/Pariwattt/CE341_ID2019/assets/149044545/270c6d1e-3932-4b7f-a7af-718c1ed2ede1)
