# คำสั่ง git ที่ใช้บ่อย

## กลุ่มงานทั่วไป Pull, Add, Commit, Status, and Push

### git pull
- ดึง contents ล่าสุดของ branch ปัจจุบัน จาก remote (origin) repository   

### git status
- ตรวจสอบสถานะของไฟล์ใน git (working directory, staging area, local repo)

### git add <file(s)>
- เพิ่มไฟล์ <file(s)> เข้าไปยัง staging areas, ใช้ git add .  เพื่อเพิ่มไฟล์ทั้งหมดใน directory

### git commit –m “<commit messages>” 
- ส่งไฟล์จาก staging area เข้าไปยัง local repo พร้อมคำอธิบายเหตุผลในการแก้ไขไฟล์

### git push
- Sync การเปลี่ยนแปลงใน local repo ไปยัง remote repository

  ![image](https://user-images.githubusercontent.com/567256/137286270-bd06980a-e69d-4951-8c56-3c4fb9de4fc9.png)
