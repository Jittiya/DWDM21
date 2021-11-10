# DWDM21
Data Warehouse &amp; Data Mining 2021

จิตติยา ศิริธรรมจักร   623021043-3

Group name **Natasha Romanoff**

1 **_จิตติยา ศิริธรรมจักร  623021043-3_**

2 จุฑากาญจน์ ชิงจันทร์     623020514-5    

3 ขนิษฐา ภูโสภา          623021042-5   

4 ชนกานต์ พูลผล         623021046-7

5 ฐิติวัฒน์ จันทรเสนา       623021047-5   

# สารบัญเนื้อหา

  ## วิชา Data Mining and Data Warehouse

  * บทที่ 1 Introduction (https://github.com/Jittiya/DWDM21/blob/ff469b4674f245df220d5e107059ff4aa02c8720/Lecture%20Chapter%201.pdf) ประกอบด้วยหัวข้อ ดังนี้
     
     * ทำไมต้องมีการทำเหมืองข้อมูล (Why Data Mining?)
     * อะไรคือเหมืองข้อมูล (What Is Data Mining?)
     * มุมมองหลายมิติของเหมืองข้อมูล (A Multi-Dimensional View of Data Mining)
     * สามารถขุดเเหมืองข้อมูลที่ไหนได้บ้าง (What Kinds of Data Can Be Mined?)
     * รูปแบบหรือทิศทางของข้อมูล (What Kinds of Patterns Can Be Mined?)
     * ใช้เทคโนโลยีประเภทใด? (What Kinds of Technologies Are Used?)
     * แอพพลิเคชั่นเป้าหมาย(What Kinds of Applications Are Targeted?)
     * ความสำคัญในการทำเหมือง(Major Issues in Data Mining)
     * ประวัติความเป็นมา(A Brief History of Data Mining and Data Mining Society)
     * สรุป (Summary)
     
  * บทที่ 2 Getting to Know Your Data มี 4 ไฟล์ ประกอบด้วยหัวข้อ ดังนี้
    
     * Basic Python (https://github.com/Jittiya/DWDM21/blob/6013a081b31d268e333fc5f87d3aa37665ebaeb9/Data101_(Chapter2).ipynb)
       * Casting (int(),str())
       * Data Structure (list(), list, วิธีการสร้าง, การชี้ค่า, Loop, Condition, Function)
     * Plot Data (https://github.com/Jittiya/DWDM21/blob/7e0f6e9c69683c86739b15e4e045514c5426372d/Data102(Chapter2).ipynb)
       * Basic Data
       * การตรวจสอบตารางข้อมูลโดยใช้ .head() & .tail()
       * Boxplot
       * Time Series Plot
     * Visualizetion (https://github.com/Jittiya/DWDM21/blob/7e0f6e9c69683c86739b15e4e045514c5426372d/Data_Visualizetion.ipynb)
       * Scatter plot (กำหนดขนาด, กำหนดสี, marker, alpha)
       * Plot
       * Bar chart (grouped, stacked)
       * Histogram
     * Distance Numpy (https://github.com/Jittiya/DWDM21/blob/7e0f6e9c69683c86739b15e4e045514c5426372d/Distance_Numpy.ipynb)
       * Numpy Array (Indexing & Slicing, Useful functions, วนลูป, Quiz กลุ่ม)
       * Distance Matrix ( Euclidean Distance (L2-norm), Distance function, Manhattan Distance (L1-norm) )
     * สไลด์ (https://github.com/Jittiya/DWDM21/blob/65f5dfea53ec2adf85f231bb5aaef073f2d2fa36/Lecture%20Chapter%202.pdf)
     
  * บทที่ 3 (https://github.com/Jittiya/DWDM21/blob/b0eb560363879f427bd56f5c741771735f0f1d8d/Data_Preprocessing(Chapter_3).ipynb) มีหัวข้อดังนี้
     * Meta Data
     * การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
       * ชี้ข้อมูลในตาราง 
         * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
         * ชี้แบบ .iloc[] (มองข้อมูลเป็น metrix)
       * Missing Value
         * Handle Missing Value 1 (ลบค่า Missing)
           * Quiz3 หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
         * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
         * Handle Missing Value 2
         * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
         * Handling Missing Value 4 (แทนด้วยค่ากลาง)
         * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
       * PANDA
         * Select data by values [PD]
         * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
       * Quiz 4 + HW
         * การต่อตารางแนวแกน Y [PD]
         * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
         * การเรียงข้อมูล [PD]
         * Outlier
       * Quiz 5
         * Quiz กลุ่ม III function box_vals
         * Pandas' looping(.iterrows)
       * การรวม 2 ตารางโดยใช้ .merge()
         * เลือกบาง column จากอีกตารางหนึ่งมาแปะ .map()
         * Group by (pandas)
         * [PD] save ตารางเอาไปใช้
         * [PD] การสร้างตาราง
     * สไลด์ 
  * บทที่ 4 Data Warehousing and On-line Anaalytical Processing ()
     * Basic Data Warehouse
       * คลังข้อมูลคืออะไร
       * วัตถุประสงค์
       * การบูรณาการ
     * Data Cube and OLAP
       * OLTP vs OLAP
       * Data Cubes
       * Conceptual Modeling of Data Warehouse
     * การออกแบบ และการใช้งานคลังข้อมูล
     * ความสำคัญของคลังข้อมูล
     * สไลด์
  * บทที่ 5 Association Rules (https://github.com/Jittiya/DWDM21/blob/65f5dfea53ec2adf85f231bb5aaef073f2d2fa36/Chapter6_Association_Rules.ipynb) มีหัวข้อดังนี้
     * ความหมาย
     * Basic concepts
       * การวาดกราฟสรุปจำนวน items และ ยอดขาย
       * การเตรียม Data สำหรับ(Fequence Pattern) Association Rule
     * Efficient Pattern Mining Methods
       * Apriori
       * Support
