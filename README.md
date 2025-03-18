# Data Structures and Algorithms
โครงสร้างข้อมูลและอัลกอริทึม

ผู้สอน: ดร.รัฐพรหม พรหมคำ


## ปีการศึกษา 2567/2
รายวิชานี้ดำเนินการสอนในรูปแบบการบรรยาย ปฏิบัติการทางคอมพิวเตอร์ 
อาจรวมถึงห้องเรียนออนไลน์หรือเป็นไปตามประกาศของทางมหาวิทยาลัยเทคโนโลยีราชมงคลธัญบุรี 


### เวลาและสถานที่เรียน

| Section | ห้องเรียน | วัน | บรรยายทฤษฏี  | ปฏิบัติการ  |
|--------|---------|----|---------------|---------------|
| 01     |  ST1905 | พุธ | 13.00 - 15.00  | 15.00 - 17.00|

สอบกลางภาค:  7 มกราคม 2568 เวลา 09.00 - 12.00

สอบปลายภาค:  11 มีนาคม 2568 เวลา 09.00 - 12.00

### ห้องเรียนออนไลน์ Microsoft Teams

| Section | Invitation Code | 
|---------|-----------------|
|     01  |  `2ewekph`      | 

กรอกรหัสการเข้าร่วม (Invitation Code) ตามที่ระบุไว้ของแต่ละ Section ที่นักศึกษาได้ลงทะเบียนไว้ เพื่อเข้าใช้งานห้องเรียนออนไลน์


## คำอธิบายรายวิชา

แนวคิดของโครงสร้างข้อมูล โครงสร้างข้อมูลเบื้องต้น การดำเนินการบนโครงสร้างข้อมูล เทคนิคการค้นและเทคนิคการเรียงลำดับ การวิเคราะห์โครงสร้างข้อมูล การประยุกต์และอัลกอริทึมสำหรับการแก้ปัญหา และปฏิบัติการที่เกี่ยวข้อง

Concepts of data structures, fundamental data structures, operations of data structures, basic searching and sorting techniques, data structure analysis, applications and problem solving algorithms and related laboratory



## จุดมุ่งหมายรายวิชา

1. CLO1: อธิบายแนวคิดเกี่ยวกับโครงสร้างข้อมูลและอัลกอริทึมได้
2. CLO2: บอกประเภทโครงสร้างข้อมูลและอัลกอริทึมสำหรับการแก้ปัญหาได้ 
3. CLO3: อธิบายการดำเนินการบนโครงสร้างข้อมูล เทคนิคการค้น การเรียงลำดับ และวิเคราะห์โครงสร้างข้อมูลได้
4. CLO4: ประยุกต์ใช้อัลกอริทึมที่เหมาะสมสำหรับการแก้ปัญหา และปฏิบัติการที่เกี่ยวข้องได้ 


## หัวข้อการบรรยาย

| Topic                    |  CLass Materials                |
|--------------------------|---------------------------------|
| Introduction to algorithms|  [Lecture](./materials/intro.pdf) <br> [Workshop 01](./materials/workshop_01.ipynb)|
| Selection sort            |  [Lecture](./materials/selection_sort.pdf)<br> [Workshop 02](./materials/workshop_02.ipynb) <br> [Workshop 03](./materials/workshop_03.ipynb) |
| Recursion                 |  [Lecture](./materials/recursion.pdf) <br> [Workshop 04](./materials/workshop_04.ipynb) |
| Quicksort                 |  [Lecture](./materials/quicksort.pdf) <br> [Workshop 05](./materials/workshop_05.ipynb) |
| Hash tables               |  [Lecture](./materials/hash_tables.pdf) <br> [Workshop 06](./materials/workshop_06.ipynb) |
| Breadth-first search      |  [Lecture](./materials/breadth_first_search.pdf) <br> [Workshop 07](./materials/workshop_07.ipynb) |
| Dijkstra's algorithm      |  [Lecture](./materials/dijkstra.pdf) <br> [Workshop 08](./materials/workshop_08.ipynb) |
<!-- | Greedy algorithm          |  [Lecture](./materials/lecture_09.pdf) <br> [Workshop 09](./materials/workshop_09.ipynb) |
| Dynamic programming       |  [Lecture](./materials/lecture_10.pdf) <br> [Workshop 10](./materials/workshop_10.ipynb) |
| K-nearest neighbors       |  [Lecture](./materials/lecture_11.pdf) <br> [Workshop 11](./materials/workshop_11.ipynb) | -->



## การวัดผลการเรียน
คะแนนเต็ม 100 คะแนน โดยแบ่งออกเป็น
- การสอบกลางภาค 25%
- การสอบปลายภาค 25%
- การสอบย่อย 25%
- งานที่ได้รับมอบหมาย 25%

หากนักศึกษาเข้าเรียนน้อยกว่า 80% ของเวลาเรียนทั้งหมด
หรือได้คะแนนรวมน้อยกว่า 50% ของคะแนนเต็ม นักศึกษาจะไม่ผ่านในรายวิชานี้ และได้รับการบันทึกผลการเรียน F (เกรด 0.0) 

สำหรับนักศึกษาที่ผ่านเกณฑ์ดังกล่าว จะได้รับการบันทึกผลการเรียนตามเกณฑ์ของคะแนน t-score 

```
t-score = 50 + 10*(x - u)/s
```
เมื่อ x คือคะแนนรวม, u คือคะแนนเฉลี่ยของคะแนนรวม และ s คือส่วนเบี่ยงเบนมาตรฐานของคะแนนรวม

ดังนี้

| ผลการเรียน | เกรด | เกณฑ์ t-score |
|---------|------|--------------|
| F | 0.00 | (-Inf, 50) | 
| D | 1.00 | [50, 55) | 
| D+ | 1.50 | [55, 60) | 
| C | 2.00 | [60, 65) |
| C+ | 2.50 | [65, 70) |
| B | 3.00 | [70, 75) |
| B+ | 3.50 | [75, 80) |
| A | 4.00 | [80, Inf) |




## เอกสารอ้างอิง
- A. Y. Bhargava, Grokking Algorithms, 2nd edition. Manning, 2024.
- T. H. Cormen, C. E. Leiserson, R. L. Rivest, and C. Stein, Introduction to Algorithms, 3rd Edition, 3rd edition. Cambridge, Mass: The MIT Press, 2009.

