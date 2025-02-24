# การติดตั้ง

ในการติดตั้ง Deployer ให้รันคำสั่งถัดไปในโปรเจ็กต์ไดเรกทอรีของคุณ::
```
composer require --dev deployer/deployer
```

ในการเริ่มต้นใช้งาน Deployer ในการรันโปรเจ็กต์ของคุณ:

```
vendor/bin/dep init
```

:::เคล็ดลับ Bash ในการรวบรวม
เพิ่มนามแฝงถัดไปในไฟล์ _.bashrc_ ของคุณ:

```bash
alias dep='vendor/bin/dep'
```

Deployer มาพร้อมกับการสนับสนุนการเติมข้อความอัตโนมัติสำหรับชื่องาน ตัวเลือก และโฮสต์

รันคำสั่งถัดไปเพื่อเพิ่มการรองรับ bash ให้สมบูรณ์:

```
dep completion bash > /etc/bash_completion.d/deployer
```

ตรวจสอบให้แน่ใจว่าไฟล์ _.bashrc_ ของคุณมีไฟล์ที่สร้างขึ้นด้วยประการใด

:::
