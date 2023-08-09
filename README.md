# ML-Homework
This is for Machine Learning Homeworks.
Data Science Bootcamp #08 - Datarockie

การบ้าน part 1 ให้ลองสร้าง regression model ทำนายราคาบ้านที่อินเดีย โดยใช้ข้อมูล dataset จาก data.world นะครับ ลิ้งด้านล่าง

https://data.world/dataindianset2000/house-price-india

สมัคร free account แล้วดาวน์โหลด Excel/ CSV ออกมาได้เลย import เข้าโปรแกรม R แล้วเขียนโมเดลด้วย caret เลือกตัวแปร 3-5 ตัว

Tip - ก่อนเราจะเทรนโมเดล ลอง visualize คอลัมน์ price จะเห็นว่าข้อมูลมันเบ้ขวามากๆ ถ้าเราอยากจะปรับให้มัน normal ขึ้น สามารถใช้ฟังก์ชัน log(price) เพื่อปรับ distribution ให้มีการกระจายตัวดีขึ้นได้ (เทคนิคนี้ในงาน ML เราใช้กันบ่อยๆ log transformation)

สำหรับการทำ log คอลัมน์นั้นต้องห้ามมีเลขศูนย์ หรือค่าติดลบนะครับ ตัวอย่างเช่นถ้า price มีค่าศูนย์อยู่ด้วย ให้เราใช้ฟังก์ชัน log(price+1) แทน เหมือนเรา +1 เข้าไปทั้งคอลัมน์
