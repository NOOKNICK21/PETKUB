# PETKUB
## แอพพลิเคชั่นยืนยันตัวตนให้กับสุนัข
### แอพพลิเคชั่นPetkub เป็นแอพพลิเคชั่นที่จัดทําขึ้นเพื่อยืนยันตัวตนให้กับสุนัขและแมวเพื่ออํานวยความสะดวกให้กับกลุ่มคนที่รักสุนัขและแมวที่มีอายุ18ปีขึ้นไปที่เป็นPet Humanization และยินยอมพร้อมที่จะจ่ายค่ายืนยันตัวตนสัตว์เลี้ยงของตนผ่านแพลตฟอร์มบริการยืนยันตัวตนโดยใช้เทคโนลียีปัญญาประดิษฐ์(AI)ในการจดจำภาพใบหน้าและลายจมูกของสุนัขและแมวมาพัฒนาร่วมกับแอพพลิเคชันของเราชื่อว่าPetkub

## Use Case Diagram
![usecase drawio](https://user-images.githubusercontent.com/114046284/198351519-1caf4a4c-8999-497a-bd4e-0120360e0286.png)

# ส่วนของฟังก์ชั่นเก็บข้อมูลใบหน้าของเจ้าของและสัตว์เลี้ยง
## User Interface Design
### เลือก Authenticate เพื่อทำการสแกนใบหน้า
![1](https://user-images.githubusercontent.com/114046284/198353464-8d4ff0f0-5d56-440f-b358-55dc1ec64d48.png)
### กล้องหน้าจะทำการตรวจจับภาพใบหน้าเพื่อทำการ Detected
![2](https://user-images.githubusercontent.com/114046284/198353719-29dd83b4-422b-420f-bbdf-45ae9b3974ad.png)
### ถ้าหากกล้องหน้าตรวจจับใบหน้าไม่พบจะให้ทำการลองอีกครั้ง
![3](https://user-images.githubusercontent.com/114046284/198353870-87861167-b86f-45c6-ad85-d07e7c409507.png)
### ทำการตรวจจับภาพใบหน้าอีกครั้งเพื่อบันทึกข้อมูล Biometrics
![4](https://user-images.githubusercontent.com/114046284/198354188-60d1933f-f93a-4213-bbf8-473a9169c5e2.png)
### ทำการตรวจจับใบหน้าสำเร็จ
![5](https://user-images.githubusercontent.com/114046284/198354358-40897742-12c8-4bc5-826c-4b02c0a2c868.png)
### เช็คการบันทึกข้อมูล Biometrics
![6](https://user-images.githubusercontent.com/114046284/198354494-80a022b4-826c-4ee1-aadb-c9faee0ed8d0.png)
### บันทึกข้อมูลเสร็จเรียบร้อย ทำการออกจากระบบ
![7](https://user-images.githubusercontent.com/114046284/198354662-66652d09-6317-4f92-919e-09f189cbe8d2.png)

### อ้างอิงจาก https://www.youtube.com/watch?v=WIkdceaOUns
