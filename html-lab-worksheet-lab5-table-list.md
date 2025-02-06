# ใบงานการทดลอง HTML

## การทดลองที่ 5: การสร้างตารางและรายการ
### วัตถุประสงค์
- เรียนรู้การสร้างตารางข้อมูล
- เรียนรู้การสร้างรายการแบบต่างๆ

### ขั้นตอนการทดลอง
1. สร้างไฟล์ tablelist.html ดังตัวอย่าง:
```html
<table border="1">
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </tbody>
</table>
```

### คำอธิบายเพิ่มเติม
- `<table>` กำหนดขอบเขตของตาราง
- `<thead>` สำหรับส่วนหัวตาราง
- `<tbody>` สำหรับเนื้อหาตาราง
- `<tr>` แทนแถว
- `<th>` แทนเซลล์หัวตาราง
- `<td>` แทนเซลล์ข้อมูล

2. การสร้างรายการ โดยเพิ่มเติม Code ในไฟล์ tablelist.html :
```html
<ul>
    <li>Unordered item 1</li>
    <li>Unordered item 2</li>
</ul>

<ol>
    <li>Ordered item 1</li>
    <li>Ordered item 2</li>
</ol>

<dl>
    <dt>Term 1</dt>
    <dd>Definition 1</dd>
    <dt>Term 2</dt>
    <dd>Definition 2</dd>
</dl>
```

### คำอธิบายเพิ่มเติม
- `<ul>` สำหรับรายการแบบไม่เรียงลำดับ
- `<ol>` สำหรับรายการแบบเรียงลำดับ
- `<dl>` สำหรับรายการแบบคำจำกัดความ
- `<li>` แทนรายการแต่ละรายการ

### แบบฝึกหัด
1. สร้างตารางแสดงข้อมูลส่วนตัว
2. สร้างรายการเมนูอาหาร

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ตารางข้อมูลส่วนตัวและตารางเมนูอาหาร</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f9f9f9;
        }
        table {
            width: 50%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        th, td {
            border: 1px solid #ddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        h2 {
            text-align: center;
            color: #333;
        }
    </style>
</head>
<body>
    <h2 style="text-align: center;">ข้อมูลส่วนตัว</h2>
    <table>
        <tr>
            <th>หัวข้อ</th>
            <th>รายละเอียด</th>
        </tr>
        <tr>
            <td>ชื่อ</td>
            <td>วุฒิชัย จันทร์เดชะ</td>
        </tr>
        <tr>
            <td>อายุ</td>
            <td>19 ปี</td>
        </tr>
        <tr>
            <td>เบอร์โทร</td>
            <td>095-834-2452</td>
        </tr>
        <tr>
            <td>อีเมล</td>
            <td>67030216@kmitl.ac.th</td>
        </tr>
    </table>
    <h2 style="text-align: center;">เมนูอาหาร</h2>
    <table>
        <tr>
            <th>ลำดับ</th>
            <th>ชื่อเมนู</th>
            <th>ระดับ</th>
            <th>ราคา</th>
        </tr>
        <tr>
            <td>1</td>
            <td>ข้าวไก่ย่าง 8 ดาว</td>
            <th>ธรรมดา-พิเศษ</th>
            <td>50-80 บาท</td>
        </tr>
        <tr>
            <td>2</td>
            <td>ข้าวคลุกมันปู</td>
            <th>ธรรมดา-พิเศษ</th>
            <td> 80-100 บาท</td>
        </tr>
        <tr>
            <td>3</td>
            <td>ข้าวไข่ไดโนเสาร์</td>
            <th>ธรรมดา-พิเศษ</th>
            <td>80-100 บาท</td>
        </tr>
        <tr>
            <td>4</td>
            <td>ข้าวหน้าปลาดุก</td>
            <th>ธรรมดา-พิเศษ</th>
            <td>70-100 บาท</td>
        </tr>
        <tr>
            <td>5</td>
            <td>ข้าวไก่อบ</td>
            <th>ธรรมดา-พิเศษ</th>
            <td>50-60 บาท</td>
        </tr>
    </table>
</body>
</html> 
```html

```
- ภาพผลลัพธ์:
[วางภาพ screenshot ที่นี่]
![image](https://github.com/user-attachments/assets/6d69e7b8-59f2-448d-8867-9b03a663ff72)

