# suwanun
หลักการออกแบบฐานข้อมูล และหลักการออกแบบ wec application ใช้ MySQL สามารถ ADD และ Delete ข้อมูลของ รายการหนังสือ
หลักการในส่วนของ code ที่สำคัญจะเป็นด้านการทำ backend  ใช้ apache โดยจะมีการ link ไปยังหน้าเว็บอื่นๆ
การเตรียมการระบบ Cloud เป็นการใช้ ec2 โดยใช้ instance type t2micro , Architecture x86 ในการทำ และ install docker environment รวมถึง git เพือ clone data มาเพื่อ deploy
การ deploy ตัว code มาทำงาน สร้างเว็บและ sql  พร้อมทั้ง dockerfile และ docker-compose.yaml 2เตรียม git ให้พร้อม สร้าง repositories suwanun
ใน Aws install docker engine ให้เรียบร้อย ใน Aws install docker compose ให้เรียบร้อย 
ใน command line git clone (https://github.com/suwanun65130208/suwanun/new/main?readme=1)
cd suwnaun 9.chmod -R 777 all file and folder docker-compose up --build
