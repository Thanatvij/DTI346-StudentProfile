# DTI346 — Assignment 2: Responsive Web Page

เว็บไซต์หน้าเดียวหัวข้อ Student Profile ของ Thanat Vijitrakanlikit ใช้ HTML + CSS เท่านั้น ไม่มี JavaScript, framework, CDN หรือขั้นตอน build

## เปิดใช้งาน

สามารถเปิด `index.html` ในเบราว์เซอร์ได้โดยตรง หรือดูเว็บไซต์ที่ deploy ผ่าน GitHub Pages ได้ที่:

**https://thanatvij.github.io/DTI346-StudentProfile/**

เว็บนี้แยกจาก Portfolio เดิมเป็น repository ของตัวเอง ทุก asset ใช้ relative path และอยู่ใน repository นี้ครบถ้วน

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

ข้อมูลอ้างอิง Resume ล่าสุดของผม  ภาพ SVG เป็นแผนภาพอธิบายลำดับการทำงานของ BloodScope ไม่ใช่ภาพหน้าจอแอปหรือผลการวินิจฉัย TDET-Scan ระบุชัดว่าเป็นแนวคิดและต้นแบบ



## Repository และการ Deploy

Repository: `Thanatvij/DTI346-StudentProfile`

เว็บไซต์ถูกเผยแพร่ด้วย **GitHub Pages** โดยใช้ branch `main` และไฟล์ใน root ของ repository

**Live Website:**  
https://thanatvij.github.io/DTI346-StudentProfile/
