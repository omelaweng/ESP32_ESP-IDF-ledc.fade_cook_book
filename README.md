แนวทางการทำงาน ESP32_ESP-IDF-ledc_fade_cook_book

ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน

โดยการทำงานของ Example นี้คือจะทำให้ led ค่อยๆสว่างขึ้นและค่อยๆดับลง

เลือก new project แล้วตั้งชื่อโปรเจค ที่เก็บโฟลเดอร์ และเลือก port

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 15 08 05" src="https://github.com/user-attachments/assets/1a3e3dcc-0c0a-404e-b9a0-68ddba987fac">

เลือกโปรเจค ledc_fade แล้วกด create project

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 17 13 32" src="https://github.com/user-attachments/assets/878ff9af-dacf-4a77-bf69-b69045f043cd">

ทำการ build,run โปรแกรม

ด้วยมีการต่อสายไฟเข้า led ดังนี้

|   GPIO 18   |   GPIO 19   |   GPIO 4   |   GPIO 5   |

ผลลัพธ์

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 17 21 21" src="https://github.com/user-attachments/assets/4557517b-6a70-4a7a-9beb-c19e3ba9d2d6">

แก้ไขเพิ่มเติม
ledc_fade_example_main.c

<img width="467" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 17 34 16" src="https://github.com/user-attachments/assets/9e408ada-cc81-4129-8ec8-0883af5e0adf">

ถ้าปรับให้ตัวเลขมากขึ้นกระบวนการต่างๆจะช้าลง
