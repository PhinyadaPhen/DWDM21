# DWDM21
Data Warehouse &amp; Data Mining

_Phinyada Phensuk 623021052-2_

Group name: Sandboxนะจ๊ะ

1. **นางสาวภิญญาดา เพ็ญสุข 623021052-2** 

2. นางสาวชนัญชิดา เมธีกุลมานิต 623020516-1

3. นางสาวณิชากร ไชยสุวรรณ 623020521-8

4. นางสาวกิตติมา อุปสุข 623021040-9

5. นางสาวนฤมล ไสยโสภณ 623021050-6

## สารบัญ
### **ทฤษฎี (เนื้อหา)** 

**1. Chapter 1 [Introduction](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter%201.pdf)**
  * Data Mining คืออะไร?
  * Data Warehouse คืออะไร?
  * ตัวอย่างข้อมูล

**2. Chapter 2 Getting to Know Your Data**
  * 2.1 (15/Jul/2021) [Ep.1](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter%202.1.pdf)
    * ขนาดของข้อมูล, ตัวอย่างข้อมูล, คุณสมบัติ, ชนิดของข้อมูล
  * 2.2 (23/Sep/2021 12:27 PM.) [Ep.2](https://github.com/PhinyadaPhen/DWDM21/blob/112dc8d58c4ec5fe6d82e9430d7c9dede6227480/Chapter%202%20End.pdf)
    * ความเหมือน ความแตกต่าง และความใกล้เคียง ระหว่างระยะห่างของจุดสองจุด
    * สูตรและตัวอย่างในการคำนวณ data
  * 2.3 (23/Sep/2021 3:44 PM.) [Ep.3](https://github.com/PhinyadaPhen/DWDM21/blob/112dc8d58c4ec5fe6d82e9430d7c9dede6227480/Chapter%202%20Dissimilarity.pdf)
    * การวัดความใกล้เคียงสำหรับ Binary Attributes, ตัวอย่างความแตกต่างระหว่างตัวแปร Binary Variables, สูตรการคำนวณ Symmetric binary & Asymmetric binary
    
**3. Chapter 3 [Data Preprocessing](https://github.com/PhinyadaPhen/DWDM21/blob/17f02cbdf246af989b1bc6bbe5f9c140c64d61a2/Chapter%203.pdf)**
  * Data Cleaning คืออะไร? หน้าที่?
  * Data Integration คืออะไร? หน้าที่?
  * Data Reduction and Tranformation คืออะไร? หน้าที่?
  * Dimensionality Reduction คืออะไร?

**4. Chapter 6 [Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods](https://github.com/PhinyadaPhen/DWDM21/blob/df5d91b54aaf8f46e00c9de4314b4c1e74b39da5/Chapter%206%20k-itemsets.pdf)**
  * Patterns คืออะไร? 
  * ตัวอย่างการนำ patterns ไปใช้ประโยชน์
  * การนำ K-itemsets มาใช้/การคำนวณหาค่า K-itemsets
  * Frequent Itemsets(Patterns) 

**5. Chapter 8 Classification:Basic Concepts**
  * 5.1 (7/Oct/2021 12:55 PM.) [Ep.1](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter%208%20Classification%20.pdf)
    * การสร้างโมเดลแบบมีผู้สอน และโมเดลแบบไม่มีผู้สอน
    * สร้างโมเดลเพื่อมาทำนายคำตอบของข้อมูล
    * Decision Tree Induction (การทำนายโดยวิธีต้นไม้ตัดสินใจ)
    * ตัวอย่างการหาคำตอบ
  * 5.2 (18/Oct/2021 8:11 PM.) [Ep.2](https://github.com/PhinyadaPhen/DWDM21/blob/450449bc472abe3e4dff9914bcaead8f34bfb1b7/Chapter%208%20Nai%CC%88ve%20Bayes%20Classifier.pdf)
    * วิธีการทำ Train-Test ข้อมูลของ Naïve Bayes Classifier
    * ตัวอย่างการคำนวณ
    * Chapter 9 Lazy Learner:Instance-Based Mathods
    * Lazy Learner คืออะไร?
    * วิธีการหาค่า K-NN (K-nearest neighbors)

**6. Chapter 8+9 [Neural Network for Classification](https://github.com/PhinyadaPhen/DWDM21/blob/ba3759af91b84491dbb0e83e224b52b0bda2a7af/Chapter%208-9%20Neural%20Network%20.pdf)**
  * องค์ประกอบของ Perceptron
  * ตัวอย่าง และผลการเรียนฟังก์ชัน AND & XOR ด้วยกฏ Perceptron
  * การหาค่า Procision/Recall + Test data เพิ่มเติม

**7. Chapter 10 [Cluster Analysis:Basic Concepts and Methods](https://github.com/PhinyadaPhen/DWDM21/blob/68e67c768bcd6e4e20b657dd4fa36ce143f0b87d/Chapter%2010%20Cluster%20Analysis%20.pdf)**
  * K-Means คืออะไร?
  * ตัวอย่างการหาค่า K-Means
  * การทำ Clustering แบบลำดับชั้น 
  * วิธีการวัดแบ่งออกเป็น External & Internal
  * การทำ Cluster ที่ดีต้องมี 4 ข้อ อะไรบ้าง?
  * ในกรณีที่เราไม่รู้แนวคำตอบสามารถทำอย่างไรได้บ้าง?

### **ปฏิบัติ (Google Colab)** 

**1. บทที่ 2**
* [Data101](https://github.com/PhinyadaPhen/DWDM21/blob/main/Data101(Chapter2).ipynb)
  * Basic Python
    * variables
  * Casting
    * int() float() str()
  * Data Structure
    * list()
  * Loop
  * Condition
    * เงื่อนไข if statement
  * Function
* [Data102](https://github.com/PhinyadaPhen/DWDM21/blob/main/Data102(Chapter2).ipynb)
  * Boxplot
  * Time Series Plot
* [Data Visualization](https://github.com/PhinyadaPhen/DWDM21/blob/main/Data_Visualization.ipynb)
  * Visualization
    * Scatter plot
    * Plot
    * Barchart
    * Stacked Barchart
    * Histogram
* [Distance Numpy](https://github.com/PhinyadaPhen/DWDM21/blob/main/Distance_Numpy.ipynb)
  * Numpy Array
  * สร้าง matrix เริ่มต้น(Zeros,ones)
  * สร้าง matrix randoom
  * matrix properties
  * Indexing & Slicing
  * Useful functions
  * วนลูปเอง (กรณีจำค่า function ไม่ได้)
  * Distance Matrix
  * Euclidean Distance (L2-norm)
  * Distance function
  * Manhattan Distance (L1-norm)
  * Distance of Binary Value

**2. บทที่ 3**
* [Data Preprocessing](https://github.com/PhinyadaPhen/DWDM21/blob/main/Data_Preprocessing(Chapter3).ipynb)
  * Meta Data
    * ชี้ข้อมูลในตารางแบบธรรมดา 
    * ชี้ข้อมูลในตารางแบบ .iloc[]
  * Missing Values
  * Handing Missing Values 1 (ลบค่า missing)
  * Handing Missing Values 1.5 (ลบค่า missing เฉพาะ column ที่สนใจ)
  * Handing Missing Values 2 (แทนด้วย class ใหม่(unknown))
  * Handing Missing Values 3 (แทนด้วย class ใหม่(ค่าที่เหมาะสม))
  * Handing Missing Values 4 (แทนด้วยค่ากลาง)
  * Handing Missing Values 5 (แทนด้วยค่ากล่าง samples ใน class เดียวกัน)
  * Select data by values [Pandas]
    * การต่อตารางในแนวแกน Y [PD]
    * การเรียงข้อมูล [PD]
    * Group by [PD]
    * การสร้างตาราง [PD]
  * Outlier

**3. บทที่ 5**
* [Association Rules](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb)
  * การลบ records ที่ถูก cancel ออก
  * การเตรียม Data สำหรับ (Fequence Pattern) Association Rule
  * Apriori
  * หา K-Itemsets

**4. บทที่ 6**
* [Classification - Decision Tree](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
  * Load data
  * Train Model
  * Plot tree
  * Evaluation
  * Advanced Tree
  * Test
* [Classification - KNN_NN](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter_7_Classification(KNN_NN).ipynb)
  * Load data
  * Split data
  * Train Model
  * Retrain & Evaluation
  * Neural Network
* [Classification - Evaluation](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter_7_Classification(Evaluation).ipynb)
  * Load data
  * การแบ่ง data
  * สร้าง Model ทำนาย

**5. บทที่ 7**
* [Clutering](https://github.com/PhinyadaPhen/DWDM21/blob/main/Chapter_8_Clustering.ipynb)
  * K-Means 
    * Generate data
    * Explore data
    * Clustering
    * Example Application(Color Quantization)
    * นับจำนวนสี
    * จัดกลุ่มสี
    * ใช้ Centroid เป็นตัวแทนสี
  * Hierachicla Clustering (เว็บไซท์เพิ่มเติม)
  * Clustering Evaluation (เว็บไซท์เพิ่มเติม)

**MiniExam**
* [Mid-term](https://github.com/PhinyadaPhen/DWDM21/blob/main/MiniExam.ipynb)

**Project**
* [FinalProject](https://github.com/PhinyadaPhen/DWDM21/blob/main/ProjectFinal.ipynb)

### **Thank You :)**
