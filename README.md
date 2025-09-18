1️. สร้างโฟลเดอร์โปรเจกต์ = 
mkdir ree_cat_house 
cd ree_cat_house
---
2️. ติดตั้ง express-generator แบบ global = 
npm i express-generator -g
---
3️. สร้างโครงสร้างโปรเจกต์ด้วย EJS = 
express --view=ejs app
---
4️. เข้าไปโฟลเดอร์แอป = 
cd app
---
5️. ติดตั้ง dependencies ของโปรเจกต์ = 
npm install
---
6️. ติดตั้ง MySQL (ถ้าต้องเชื่อมฐานข้อมูล) = 
npm i mysql
---
7️. ติดตั้ง Nodemon (เพื่อรีโหลดอัตโนมัติเวลามีการแก้ไขไฟล์) = 
npm i nodemon
---
8️. รันโปรเจกต์ด้วย Nodemon = 
npx nodemon
---
