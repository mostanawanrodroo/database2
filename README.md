# Database กลุ่ม มอส เตือนอุณหภูมิด้วยLED

อุปกรณ์

1.node MCU (ช่วยประมวณผล)

2.จอ LCD (แสดงผล)

3.DHT11 (วัดอุณหภูมิ)

4.หลอด LED 

5.สายไฟ 


วิธีต่อ node MCU กับ จอ LCD


![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%95%E0%B9%88%E0%B8%AD%20node%20MCU%20%E0%B8%81%E0%B8%B1%E0%B8%9A%20%E0%B8%88%E0%B8%AD%20LCD.jpg?raw=true)
.......................................................................................................................................
 
DHT11

<a href="http://www.mx7.com/view2/A2v6md22PxdZfQLa" target="_blank"><img border="0" src="http://www.mx7.com/i/0a4/5pnkIF.png" /></a>
.......................................................................................................................................

วิธีการต่อใช้งานครับ

<a href="http://www.mx7.com/view2/A2v75Wi1ptvOEn2u" target="_blank"><img border="0" src="http://www.mx7.com/i/05d/GjLehl.gif" /></a>

ในการการต่อวัดแบบปกติ คือ ระยะห่างระหว่าง Sensor กับตัว Arduino ห่างกันไม่เกิน 20 เมตร จะต้องใช้ Pull up resistor ขนาด 5kohm 
   Pin 1  ต่อกับ VDD

   Pin 2  ต่อเป็นขา DATA

   Pin 3  ไม่ได้ใช้

   Pin 4  ลงกราวด์

โดยใช้แหล่งจ่ายแรงดัน VDD ขนาด 3-5.5 VDC ซึ่งข้อดีคือจะทำให้ DHT11 นี้สามารถใช้งานได้กับ Arduino หลายรุ่น แต่ในที่นี้เราจะใช่ Arduno NodeMCU
.......................................................................................................................................


วิธี ดู fingerprint ของเว็บเรา ครับ แต่ต้องเป็นตัวใหญ่ ทั้งหมด

![alttext](https://github.com/jokermarkk/Database/blob/master/1%20fingerprint.jpg)

![alttext](https://github.com/jokermarkk/Database/blob/master/2%20fingerprint.jpg)

.......................................................................................................................................

ความคิดสร้างสรรค์

เปิด - ปิด หลอด LED ผ่าน Firebase
วิธีการต่อขาหลอดLED

![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%AB%E0%B8%A5%E0%B8%AD%E0%B8%94%E0%B9%84%E0%B8%9F.jpg)

<a href="http://www.mx7.com/view2/A3hs8JlDpk6RonNX" target="_blank"><img border="0" src="http://www.mx7.com/i/2b3/94sdkd.jpg" /></a>
รายชื่อ สมาชิก
1.นายธนวันต์   รอดรู้ 57523206053-4 วศบ.คพ.ส4

2.นายธนสินธุ์   ปัญญาดี 57523206057-5 วศบ.คพ.ส4

3.นายสุรพงษ์   บุตรแก้ว 57523206075-7 วศบ.คพ.ส4

4.นายนิรันดร์    ฟุ้งศิริกุล 57523206020-3 วศบ.คพ.4

5.นายจตุรวัฒน์   อินทร์แก้ว 57523206006-2 วศบ.คพ.4
