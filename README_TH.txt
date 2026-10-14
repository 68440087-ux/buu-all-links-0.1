BUU ALL LINKS — ชุดไฟล์ Web App / PWA

ไฟล์ในชุดนี้:
- index.html: หน้าเว็บ ค้นหาเว็บไซต์ และกรองตามหมวดหมู่
- manifest.webmanifest: ตั้งค่าการติดตั้งเป็นเว็บแอป
- sw.js: Service worker สำหรับแคชไฟล์หน้าเว็บ
- icons/: ไอคอนสำหรับเว็บและ PWA

วิธีเผยแพร่ฟรีผ่าน GitHub Pages (ทำบนมือถือหรือคอมพิวเตอร์ได้):
1. แตกไฟล์ ZIP นี้ก่อน
2. เปิด Repository ของคุณบน github.com
3. เลือก Add file > Upload files
4. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดที่อยู่ข้างใน ZIP นี้ โดยให้ index.html, manifest.webmanifest และ sw.js อยู่ที่ระดับแรก (root) ของ Repository
5. กด Commit changes
6. เข้า Settings > Pages
7. ใน Build and deployment เลือก Source = Deploy from a branch
8. เลือก Branch = main และ Folder = /(root) แล้วกด Save
9. รอการเผยแพร่ จากนั้นกด Visit site

หมายเหตุ:
- GitHub Pages ให้บริการเว็บแบบ static ฟรีสำหรับ repository สาธารณะตามข้อกำหนดของ GitHub.
- PWA ต้องเปิดผ่าน HTTPS เพื่อให้ service worker ทำงานได้; GitHub Pages ใช้ HTTPS.
- ลิงก์ในหน้าเว็บเป็นรายการเริ่มต้น และควรเทียบกับรายการ BUU All Links ต้นฉบับก่อนเผยแพร่ให้คนอื่นใช้.
