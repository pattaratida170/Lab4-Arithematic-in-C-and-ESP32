### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนถุงลูกอม
```c
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```
```
I (11505) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (11505) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (11505) CANDIES_MATH:    = 7 × 8
I (11505) CANDIES_MATH:    = 56 เม็ด
I (11505) CANDIES_MATH: 
I (11505) CANDIES_MATH: ✅ คำตอบ:
I (11505) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (11505) CANDIES_MATH: 
I (11505) CANDIES_MATH: 🎨 ภาพประกอบ:
I (11505) CANDIES_MATH:    ถุงที่ 1: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 2: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 3: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 4: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 5: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 6: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    ถุงที่ 7: 🍬 x8 เม็ด
I (11505) CANDIES_MATH:    รวมทั้งหมด: 56 เม็ด
I (11505) CANDIES_MATH: 
I (11505) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (11505) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (11505) CANDIES_MATH:                   8
I (11515) CANDIES_MATH:                 + 8
I (11515) CANDIES_MATH:                 + 8
I (11515) CANDIES_MATH:                 + 8
I (11515) CANDIES_MATH:                 + 8
I (11515) CANDIES_MATH:                 + 8
I (11515) CANDIES_MATH:                 + 8 = 56
I (11515) CANDIES_MATH:    ✅ ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (11515) CANDIES_MATH: 
I (11515) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (11515) CANDIES_MATH:    1 × 8 = 8
I (11815) CANDIES_MATH:    2 × 8 = 16
I (12115) CANDIES_MATH:    3 × 8 = 24
I (12415) CANDIES_MATH:    4 × 8 = 32
I (12715) CANDIES_MATH:    5 × 8 = 40
I (13015) CANDIES_MATH:    6 × 8 = 48
I (13315) CANDIES_MATH:    7 × 8 = 56
I (13615) CANDIES_MATH:    8 × 8 = 64
I (13915) CANDIES_MATH:    9 × 8 = 72
I (14215) CANDIES_MATH:    10 × 8 = 80
I (14515) CANDIES_MATH: 
I (14515) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (14515) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (14515) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (14515) CANDIES_MATH:
I (14515) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (14515) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (14515) CANDIES_MATH: 
I (14515) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (14515) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (14515) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (14515) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (14515) CANDIES_MATH: 
I (14515) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (14515) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (14515) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (14515) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (14515) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (14515) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (14515) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (14515) CANDIES_MATH: 
I (14515) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (14515) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (14525) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (14525) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (14525) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (14535) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (14535) CANDIES_MATH: 
I (14535) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (14535) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (16535) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 2: เพิ่มลูกอมหลายรส
เพิ่มลูกอมหลายรส:
```c
int strawberry_bags = 3;    // ถุงรสสตรอเบอร์รี่
int orange_bags = 2;        // ถุงรสส้ม
int grape_bags = 4;         // ถุงรสองุ่น

int total_bags = strawberry_bags + orange_bags + grape_bags;
int total_candies = total_bags * candies_per_bag;

ESP_LOGI(TAG, "🍓 สตรอเบอร์รี่: %d ถุง = %d เม็ด", 
         strawberry_bags, strawberry_bags * candies_per_bag);
ESP_LOGI(TAG, "🍊 รสส้ม: %d ถุง = %d เม็ด", 
         orange_bags, orange_bags * candies_per_bag);
ESP_LOGI(TAG, "🍇 รสองุ่น: %d ถุง = %d เม็ด", 
         grape_bags, grape_bags * candies_per_bag);
```
```
I (11129) CANDIES_MATH: 🧮 การคำนวณ:
I (11129) CANDIES_MATH:    7 × 8 = 56 เม็ด
I (11129) CANDIES_MATH: 
I (11129) CANDIES_MATH: 🎨 ภาพประกอบ:
I (11129) CANDIES_MATH:    ถุงที่ 1: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 2: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 3: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 4: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 5: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 6: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    ถุงที่ 7: 🍬 x8 เม็ด
I (11129) CANDIES_MATH:    รวม: 56 เม็ด
I (11129) CANDIES_MATH: 
I (11129) CANDIES_MATH: 🔄 การบวกซ้ำ:
I (11129) CANDIES_MATH:                   8
I (11129) CANDIES_MATH:                 + 8
I (11129) CANDIES_MATH:                 + 8
I (11129) CANDIES_MATH:                 + 8
I (11129) CANDIES_MATH:                 + 8
I (11129) CANDIES_MATH:                 + 8
I (11129) CANDIES_MATH:                 + 8 = 56
I (11129) CANDIES_MATH:    ✅ ผลลัพธ์เหมือนกัน: 56
I (11129) CANDIES_MATH: 
I (11129) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (11129) CANDIES_MATH:    1 × 8 = 8
I (11229) CANDIES_MATH:    2 × 8 = 16
I (11329) CANDIES_MATH:    3 × 8 = 24
I (11429) CANDIES_MATH:    4 × 8 = 32
I (11529) CANDIES_MATH:    5 × 8 = 40
I (11629) CANDIES_MATH:    6 × 8 = 48
I (11729) CANDIES_MATH:    7 × 8 = 56
I (11829) CANDIES_MATH:    8 × 8 = 64
I (11929) CANDIES_MATH:    9 × 8 = 72
I (12029) CANDIES_MATH:    10 × 8 = 80
I (12129) CANDIES_MATH: 
I (12129) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (12129) CANDIES_MATH:    3 ถุง × 8 เม็ด = 24 เม็ด
I (12129) CANDIES_MATH:    7 ถุง × 4 เม็ด = 28 เม็ด
I (12129) CANDIES_MATH: 
I (12129) CANDIES_MATH: 🎓 ความรู้ที่ได้:
I (12129) CANDIES_MATH:    - การคูณ = บวกซ้ำ
I (12129) CANDIES_MATH:    - สูตรคูณและการใช้ loop
I (12129) CANDIES_MATH:    - คำตอบจากคูณ = รวมลูกอมทั้งหมด
I (12129) CANDIES_MATH: 
I (12129) CANDIES_MATH: 📖 แบบฝึกหัดที่ 2: ลูกอมหลายรส
I (12129) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (12129) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (12139) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (12139) CANDIES_MATH: 
I (12139) CANDIES_MATH: 🎯 รวมถุงลูกอมหลายรส: 9 ถุง
I (12139) CANDIES_MATH: 🎯 รวมลูกอมทั้งหมด: 9 × 8 = 72 เม็ด
I (12139) CANDIES_MATH: 
I (12139) CANDIES_MATH: 📚 สรุปความรู้:
I (12139) CANDIES_MATH:    1. การคูณคือการบวกซ้ำ
I (12139) CANDIES_MATH:    2. ใช้ตัวแปรคำนวณของหลายประเภท
I (12139) CANDIES_MATH:    3. รวมจำนวนถุงจากหลายกลุ่มได้
I (12139) CANDIES_MATH: 
I (12139) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมทั้งหมด!
I (12139) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (15139) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 3: สร้างตารางสูตรคูณ
เพิ่มการแสดงตารางสูตรคูณ:
```c
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```
```
I (10255) CANDIES_MATH: 🧮 การคำนวณ:
I (10255) CANDIES_MATH:    7 × 8 = 56 เม็ด
I (10255) CANDIES_MATH:
I (10255) CANDIES_MATH: 🎨 ภาพประกอบ:
I (10255) CANDIES_MATH:    ถุงที่ 1: 🍬 x8 เม็ด
I (10255) CANDIES_MATH:    ถุงที่ 2: 🍬 x8 เม็ด
I (10255) CANDIES_MATH:    ถุงที่ 3: 🍬 x8 เม็ด
I (10255) CANDIES_MATH:    ถุงที่ 4: 🍬 x8 เม็ด
I (10255) CANDIES_MATH:    ถุงที่ 5: 🍬 x8 เม็ด
I (10265) CANDIES_MATH:    ถุงที่ 6: 🍬 x8 เม็ด
I (10265) CANDIES_MATH:    ถุงที่ 7: 🍬 x8 เม็ด
I (10265) CANDIES_MATH:    รวม: 56 เม็ด
I (10265) CANDIES_MATH:
I (10275) CANDIES_MATH: 🔄 การบวกซ้ำ:
I (10275) CANDIES_MATH:                   8
I (10275) CANDIES_MATH:                 + 8
I (10275) CANDIES_MATH:                 + 8
I (10275) CANDIES_MATH:                 + 8
I (10275) CANDIES_MATH:                 + 8
I (10275) CANDIES_MATH:                 + 8
I (10275) CANDIES_MATH:                 + 8 = 56
I (10275) CANDIES_MATH:    ✅ ผลลัพธ์เหมือนกัน: 56
I (10275) CANDIES_MATH: 
I (10275) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (10275) CANDIES_MATH:    1 x 8 = 8
I (10475) CANDIES_MATH:    2 x 8 = 16
I (10675) CANDIES_MATH:    3 x 8 = 24
I (10875) CANDIES_MATH:    4 x 8 = 32
I (11075) CANDIES_MATH:    5 x 8 = 40
I (11275) CANDIES_MATH:    6 x 8 = 48
I (11475) CANDIES_MATH:    7 x 8 = 56
I (11675) CANDIES_MATH:    8 x 8 = 64
I (11875) CANDIES_MATH:    9 x 8 = 72
I (12075) CANDIES_MATH:    10 x 8 = 80
I (12275) CANDIES_MATH: 
I (12275) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (12275) CANDIES_MATH:    3 ถุง × 8 เม็ด = 24 เม็ด
I (12275) CANDIES_MATH:    7 ถุง × 4 เม็ด = 28 เม็ด
I (12275) CANDIES_MATH:
I (12275) CANDIES_MATH: 🎓 ความรู้ที่ได้:
I (12275) CANDIES_MATH:    - การคูณ = บวกซ้ำ
I (12275) CANDIES_MATH:    - สูตรคูณและการใช้ loop
I (12275) CANDIES_MATH:    - คำตอบจากคูณ = รวมลูกอมทั้งหมด
I (12275) CANDIES_MATH: 
I (12275) CANDIES_MATH: 📖 แบบฝึกหัดที่ 2: ลูกอมหลายรส
I (12275) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (12275) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (12275) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (12275) CANDIES_MATH: 
I (12275) CANDIES_MATH: 🎯 รวมถุงลูกอมหลายรส: 9 ถุง
I (12275) CANDIES_MATH: 🎯 รวมลูกอมทั้งหมด: 9 × 8 = 72 เม็ด
I (12275) CANDIES_MATH:
I (12275) CANDIES_MATH: 📚 สรุปความรู้:
I (12275) CANDIES_MATH:    1. การคูณคือการบวกซ้ำ
I (12275) CANDIES_MATH:    2. ใช้ตัวแปรคำนวณของหลายประเภท
I (12275) CANDIES_MATH:    3. รวมจำนวนถุงจากหลายกลุ่มได้
I (12275) CANDIES_MATH:    4. ตารางสูตรคูณช่วยให้จำค่าได้เร็วขึ้น
I (12275) CANDIES_MATH: 
I (12275) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมทั้งหมด!
I (12275) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (15275) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 4: แจกลูกอมให้เพื่อน
คำนวณการแจกลูกอม:
```c
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```
```
I (8827) CANDIES_MATH: 🧮 การคำนวณ:
I (8827) CANDIES_MATH:    7 × 8 = 56 เม็ด
I (8827) CANDIES_MATH: 
I (8827) CANDIES_MATH: 🎨 ภาพประกอบ:
I (8827) CANDIES_MATH:    ถุงที่ 1: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 2: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 3: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 4: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 5: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 6: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    ถุงที่ 7: 🍬 x8 เม็ด
I (8827) CANDIES_MATH:    รวม: 56 เม็ด
I (8827) CANDIES_MATH: 
I (8827) CANDIES_MATH: 🔄 การบวกซ้ำ:
I (8827) CANDIES_MATH:                   8
I (8827) CANDIES_MATH:                 + 8
I (8827) CANDIES_MATH:                 + 8
I (8827) CANDIES_MATH:                 + 8
I (8827) CANDIES_MATH:                 + 8
I (8827) CANDIES_MATH:                 + 8
I (8827) CANDIES_MATH:                 + 8 = 56
I (8827) CANDIES_MATH:    ✅ ผลลัพธ์เหมือนกัน: 56
I (8827) CANDIES_MATH:
I (8827) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (8827) CANDIES_MATH:    1 x 8 = 8
I (9027) CANDIES_MATH:    2 x 8 = 16
I (9227) CANDIES_MATH:    3 x 8 = 24
I (9427) CANDIES_MATH:    4 x 8 = 32
I (9627) CANDIES_MATH:    5 x 8 = 40
I (9827) CANDIES_MATH:    6 x 8 = 48
I (10027) CANDIES_MATH:    7 x 8 = 56
I (10227) CANDIES_MATH:    8 x 8 = 64
I (10427) CANDIES_MATH:    9 x 8 = 72
I (10627) CANDIES_MATH:    10 x 8 = 80
I (10827) CANDIES_MATH: 
I (10827) CANDIES_MATH: 📖 แบบฝึกหัดที่ 2: ลูกอมหลายรส
I (10827) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (10827) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (10827) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (10827) CANDIES_MATH: 
I (10827) CANDIES_MATH: 🎯 รวมถุงลูกอมหลายรส: 9 ถุง
I (10827) CANDIES_MATH: 🎯 รวมลูกอมทั้งหมด: 9 × 8 = 72 เม็ด
I (10827) CANDIES_MATH:
I (10827) CANDIES_MATH: 👥 แจกลูกอมให้เพื่อน 12 คน:
I (10837) CANDIES_MATH:    แต่ละคนจะได้: 6 เม็ด
I (10837) CANDIES_MATH:    ลูกอมที่เหลือ: 0 เม็ด
I (10837) CANDIES_MATH: 
I (10837) CANDIES_MATH: 📚 สรุปความรู้:
I (10837) CANDIES_MATH:    1. การคูณคือการบวกซ้ำ
I (10837) CANDIES_MATH:    2. รวมลูกอมจากหลายกลุ่ม
I (10837) CANDIES_MATH:    3. หารเพื่อแจกให้เพื่อน = ใช้ / และ %
I (10837) CANDIES_MATH: 
I (10837) CANDIES_MATH: 🎉 จบโปรแกรมนับและแจกลูกอม!
I (10847) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (13847) main_task: Returned from app_main()
```
