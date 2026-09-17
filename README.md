# DTI346 — Assignment 2: Responsive Web Page

เว็บไซต์หน้าเดียวหัวข้อ Student Profile ของ Thanat Vijitrakanlikit ใช้ HTML + CSS เท่านั้น ไม่มี JavaScript, framework, CDN หรือขั้นตอน build

## เปิดใช้งาน

เปิด `index.html` ในเบราว์เซอร์ได้โดยตรง เว็บนี้แยกจาก Portfolio เดิมเป็น repository ของตัวเอง ทุก asset ใช้ relative path และอยู่ใน repository นี้ครบถ้วน

## ข้อกำหนด (เอกสาร Week 5 หน้า 82)

| ข้อกำหนด | ตำแหน่งที่ใช้ |
| --- | --- |
| Semantic HTML | header, nav, main, section, article, figure, footer |
| Viewport | meta viewport ใน head |
| Flexbox / Grid | เมนู, hero-grid, project-cards, skill-grid |
| Mobile-first | CSS เริ่มที่หนึ่งคอลัมน์ |
| Media queries | 768px และ 1100px |
| Layout เปลี่ยนชัดเจน | Hero 1 → 2 คอลัมน์, project cards 1 → 2 → 3 คอลัมน์ |
| Responsive image + alt | assets/bloodscope-pipeline.svg แสดงผ่าน img พร้อม width, height, alt และ max-width:100%; height:auto |
| Mobile usability | ปุ่มหลักอย่างน้อย 50px, เมนูและลิงก์สำคัญอย่างน้อย 44px, focus-visible, skip link, reduced motion |
| Action | ลิงก์ผลงาน, อีเมล, Resume PDF, GitHub, LinkedIn และเกียรติบัตร |

## เนื้อหาและภาพ

ข้อมูลอ้างอิง Resume ล่าสุดที่ผู้ใช้ให้ไว้ (Word_MYResume.pdf) ภาพ SVG เป็นแผนภาพอธิบายลำดับการทำงานของ BloodScope ไม่ใช่ภาพหน้าจอแอปหรือผลการวินิจฉัย TDET-Scan ระบุชัดว่าเป็นแนวคิดและต้นแบบ

โฟลเดอร์นี้เป็นเว็บแยกสำหรับ DTI346 โดยเฉพาะ ไม่ต้องใช้ไฟล์หรือสคริปต์จาก Portfolio เดิม


## เผยแพร่ใน repository ใหม่

ชื่อแนะนำ: `dti346-student-profile` (ยังไม่ได้สร้างบน GitHub)

1. สร้าง repository ว่างชื่อ `dti346-student-profile` ในบัญชี Thanatvij
2. นำไฟล์ในโฟลเดอร์นี้ขึ้น repository โดยให้ `index.html`, `styles.css` และ `assets/` อยู่ระดับราก ไม่ต้องซ้อนโฟลเดอร์ `dti346/`
3. ไปที่ Settings → Pages → Deploy from a branch → main → /(root) แล้ว Save
4. เมื่อ GitHub Pages เผยแพร่สำเร็จ URL มาตรฐานจะเป็น `https://thanatvij.github.io/dti346-student-profile/`

Portfolio เดิมยังอยู่ที่ repository `Thanatvij.github.io` แยกประวัติ Git และการ deploy กัน แม้ URL จะอยู่ภายใต้โดเมน github.io เดียวกัน


