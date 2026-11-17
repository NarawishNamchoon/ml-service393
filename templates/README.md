# Model as a Service ด้วย Flask และ Docker

โปรเจกต์ให้บริการโมเดลทำนายราคาบ้านในแคลิฟอร์เนีย (California Housing) ผ่านเว็บ Flask และ Docker

## วิธี Build
```
docker build -t ds-ml-service .
```

## วิธี Run
```
docker run --rm -p 5000:5000 ds-ml-service
```
เปิดเบราว์เซอร์ที่ http://127.0.0.1:5000/

## ผลลัพธ์ 
![ผลการทำนาย](result.png)

ผลการทำนายจากค่าตัวอย่าง (Use sample values): ประมาณ 4.029