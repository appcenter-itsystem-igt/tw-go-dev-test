
## แบบทดสอบ

ให้เขียน Rest API ด้วย ภาษา GO ใช้ package Fiber เป็นหลักและเชื่อมต่อฐานข้อมูลจากไฟล์ dataset.csv และสามารถใช้ ai ช่วยในการเขียนได้ โดยมีเงื่อนไขดังนี้

`1. GET /products/:id` สามาถเรียกดูข้อมูลได้ตาม id

`2. GET /products` สามาถเรียกดูข้อมูลได้ทั้งหมด

`3. POST /products` สามารถเพิ่มข้อมูลลงในไฟล์ได้

`4. PATCH /products/:id` สามาถแก้ไขข้อมูลในไฟล์ได้ตาม id

`5. PATCH /products` สามาถแก้ไขข้อมูลในไฟล์กี่แถวก็ได้ตาม parameter ที่ระบุ

`6. DELETE /products/:id` สามาถลบข้อมูลในไฟล์ได้ตาม id

`7.` สร้าง file log.txt เก็บข้อมูลประวัติการ request เฉพาะ  POST, PATCH และ DELETE

`8.` สร้าง key พิเศษ ในการป้องกันการเข้าถึง api ที่ไม่ได้รับอนุญาต (รูปแบบใดก็ได้)

`9.` ให้เขียนโปรแกรมโดยใช้แนวคิด  Clean Architecture

`10.` ทดสอบ api แต่ละ method โดยใช้ postman พร้อมทั้งอธิบาย code และหลักการที่เขียนมา (capure video screen) ชื่อไฟล์ test_result.mp4



## วิธีการส่งแบบทดสอบ

1 . สร้าง GitHub repository ชื่อ tw-go-dev-test-“yourname” 

```bash
  tw-go-dev-test-somchai
```

2 . ใน repository มี folder เหมือนกับ repo ข้อสอบ ดังนี้

```bash
tw-go-dev-test-somchai
├── code
│   ├── example.go (ตัวอย่างชื่อไฟล์)
│   └── .......
├── database
│   └── dataset.csv
├── results
│   └── test_result.mp4
└── README.md
```

## หมายเหตุ
- ในข้อที่ `10` สามารถทดสอบ api พร้อมทั้งอธิบาย code แบบ (online meeting) โดยให้ระบุวันนัดหมาย ในวันที่ส่งแบบทดสอบ หลังจากนั้นผู้ตรวจแบบทดสอบ จะส่ง email นัดหมายเพื่อทดสอบ api และประเมินผลการทดสอบในลำดับถัดไป

