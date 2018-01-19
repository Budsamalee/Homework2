# Homework2 

# <h1> Git hub ? </h1>
Github คือ เว็ปไซต์ที่ทำให้เราสามารถใช้ Git ร่วมกับคนอื่นได้ หรือพูดง่ายๆก็คือ Git ที่อยู่บนเว็บไซต์นั่นเอง เป็นเว็บเซิฟเวอร์ที่ให้บริการในการฝากไฟล์ Git
★ ตัวอย่าง    --->  การก็บโปรเจ็ค Open Source 
★ ข้อดี         --->  ใช้ฟรี และสร้าง repository ได้ไม่จำกัด
# Create Repo
เป็นการสร้าง repository โดยจะเอาโค๊ดที่ได้เขียนไว้  คือ โปรเจค Homework2 ที่ได้สร้างขึ้นมานั้นเอง มันจะถูกอัพโหลดขึ้นเซิฟเวอร์ 
▂ ▃ ▄ ▅ ▆ ▇ █ เรามาทำความรู้จักคำสั่งแต่ละคำสั่งกันดีว่า █ ▇ ▆ ▅ ▄ ▃ ▂ 
# mkdir Homework2
★เป็นการสร้างไดเร็กทอรี่ ที่มีชื่อ Homework2
# cd Homework2
★ เพื่อเข้าไฟล์ไปยัง dir ที่มีชื่อ Homework2
# echo "# Homework2" >> README.md
★ เปรียบเสมือนคำสั่งที่ใช้ในการแสดงผล
# git init
★ เอาไว้เพื่อสร้าง git repository เปล่าๆขึ้นมา โดย Git จะทำการสร้างโฟลเดอร์  .git ขึ้นมาภายในโปรเจ็คของเรา (Hidden ไว้อยู่)
# git add README.md
★ เป็นคำสั่งใช้ stage เพื่อติดตามตามความเปลี่ยนแปลงของไฟล์
# git status
★ เพื่อตรวจสอบสถานะ  repository ของเรา 
# git config --global user.email "5835512056@psu.ac.th"
★ เป็นคำสั่งที่ใช้เพื่อระบุที่อยูผู้ใช้่อีเมลอ ย่างชัดเจน
# git config --global user.name "Budsamalee"
★ เป็นคำสั่งที่ใช้เพื่อระบุชื่อผู้ใช้ อย่างชัดเจน 
# git commit -m "first commit"
★ ใช้เพื่อบันทึกความเปลี่ยนแปลงที่เกิดขึ้นสู่ local repo
# git remote add origin https://github.com/Budsamalee/Homework2.git
★ เมื่อยังไม่มี remote repo เราก็จะเพิ่มมันเข้าไป โดยใช้ url ที่ก็อปปี้ไว้เมื่อกี้
# git remote -v
★ เพื่อเช็คว่า local repo นี้มี remote repo รึยัง
# git push -u origin master
★ ใช้เพื่อส่ง commit ไปยัง remote repo





		
