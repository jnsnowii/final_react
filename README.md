#Final React : Smallroom

สมาชิกในกลุ่ม

นางสาวธนพร ธีระไชยกุล 57080501621
นายนิตินัย ศินสุขภิรมย์ 57080501669
นายเมธี เพชรสังฆาต 57080501685
นางสาววิภาวี ถวิลวงศ์รักษ์ 57080501688

วิธีการติดตั้ง

หลังจากแตกไฟล์หรือ git clone ให้เปิด command หรือ terminal จากนั้น cd เข้าไปใน folder ของ project นี้จากนั้นพิมพ์คำสั่ง 

 npm install 
Android

โหลดโปรแกรม Genymotion มา แล้วกด add เพื่อเพิ่ม virtual device เลือก device model เป็น custom phone และ android version 5.10
จากนั้น select device แล้วกด start จะขึ้นหน้าต่าง emulator ที่ยังไม่ได้รันโปรเจกต์
ที่ terminal เปิด packager เพื่อเปิด server

 react-native start 
แล้วเปิด command หรือ terminal ขึ้นมาใหม่อีก 1 อัน cd เข้าไปใน folder ของ project จากนั้นพิมพ์คำสั่ง
 react-native run-android 
โปรเจกต์จะรันบน Genymotion โดยอัตโนมัติ

IOS

 react-native run-ios 
