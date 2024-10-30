## แนวทางการทำงาน ESP32 project cook book
1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
   - เอามาจากตัวอย่าง softAp ของ wifi
     ![image](https://github.com/user-attachments/assets/81fa0fe6-d12b-4061-bac3-22630071b2c5)
2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร
   - แก้ไขในส่วนของ config แล้วค้นหาตัว WiFi กดเลือกแก้ไขตามรูป
     ![image](https://github.com/user-attachments/assets/dd4b4dbf-e0ec-4fdc-8d95-0d447db49dff)
   - ทำการแก้ไขเรียบร้อยแล้วให้กด save เพื่อยืนยันในการสร้าง WiFi
3. แสดงขั้นตอนการทำ project
   - เลือก example กดค้นหา softAP ของ wifi
   - ทำการเปลี่ยนwifiในเมนู config ตามข้อที่2
   - อย่าลืมเลือก comportให้ถูกต้อง อย่างตัวอย่างนี้ใช้ com3
   - ทำการ build หลังจากเรียบร้อยแล้วทำการ flash และ monitor
   - เปิดดูWiFiในมือถือกดเลือก WiFiจะขึ้นมาใส่รหัสและทำการconnect
   - เพียงเท่านี้ก็จะสามารถเชื่อมต่อกับWiFi ที่สร้างขึ้นมาบนตัว ESP32
  4. แสดงผลการทำ project
   - ผลลัพธ์หน้าจอบน vscode
     ![image](https://github.com/user-attachments/assets/e5737d64-8519-4f8d-b7e0-677c8838e27b)
   - ผลลัพธ์บนอุปกรณ์มือถือ
     ![image](https://github.com/user-attachments/assets/5cc2a5a0-429c-4490-a9c3-b0283f8a5956)


5. สรุปผลการทำ project
   - ใช้esp32ทำหน้าที่เป็น Access Point (AP) ให้กับอุปกรณ์อื่น ๆ โดยตรง เช่น สมาร์ทโฟน แล็ปท็อป
   - ไปประยุกต์ใช้ในการควบคุมsmart homeควบคุมการเปิดปิดไฟ เครื่องใช้ไฟฟ้าในบ้าน ต่างๆ 
