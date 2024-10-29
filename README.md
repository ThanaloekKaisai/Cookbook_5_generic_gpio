# Example นี้คือ generic_gpio
โค้ดทดสอบนี้แสดงวิธีการกำหนดค่า GPIO และวิธีการใช้งานร่วมกับการหยุดชะงัก (interruption)

Show Example แล้วเลือก generic_gpio

![image](https://github.com/user-attachments/assets/03c8f0b8-3897-4d01-bc88-6a47999f6434)

จากนั้นให้เซ็ทขา GPIO ตามต้องการในที่นี้เป็น

![image](https://github.com/user-attachments/assets/dd9935d8-a1db-4352-b32d-3f868e39e493)

ให้ต่อขา Input 0 เข้ากับ Output 0 และ Input 1 กับ Output 1

สังเกตุใน Serial Moniter จะเป็นการแสดงสถานะของขา Input และ Output ที่เชื่อมต่อกันอยู่

![image](https://github.com/user-attachments/assets/74124b55-dc11-4d37-8cd7-689984e7fb0a)

ลองถอดและเสียบขา GPIO สลับกันไปมาสถานะของ Input และ Output จะเปลี่ยนแปลง
