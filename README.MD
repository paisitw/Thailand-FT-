การแปลงค่า FT จาก text เป็น float เพื่อนำไปคำนวนในจุดประสงค์ต่างๆ

- เอาค่า raw FT ที่ดึงมาจาก https://www.pea.co.th/our-services/tariff/ft
- การดึงค่านั้นทำโดยผ่าน Scrape integration ใน Home Assistant ซึ่งเป็น text
- ตัวอย่าง code นี้ก็จะมาแปลง text เป็น float ที่มีจุดทศนิยม 4 จุด
- เอา code ไปใส่ไว้ใน configuration.yaml หรือ ถ้าแยก yaml ไฟล์เช่นมี sensors.yaml 
  ก็ให้ตัด sensors: ด้านบนสุดออกไป
