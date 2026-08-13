# แผนงานทั้งหมด (Project Plan)
## การพัฒนาเว็บไซต์ ComInnoCenter แบบ Premium

**โครงการ**: Redesign เว็บไซต์ Center of Excellence in Communication Innovation  
**เป้าหมาย**: สร้างเว็บไซต์ระดับพรีเมียมที่สะท้อนความเป็นเลิศทางวิชาการ + นวัตกรรมสื่อสาร + Sustainability  
**อัปเดตล่าสุด**: 13 สิงหาคม 2569

---

## ภาพรวมเฟสงาน (High-Level Phases)

| เฟส | ชื่อเฟส | ระยะเวลาโดยประมาณ | สถานะ |
|-----|---------|------------------|--------|
| 0 | Discovery & Archive | เสร็จแล้ว | ✅ Done |
| 1 | Strategy & Design Foundation | 1–2 สัปดาห์ | ⏳ Next |
| 2 | Information Architecture & Content Strategy | 1 สัปดาห์ | Pending |
| 3 | Visual Design (UI/UX + Design System) | 2–3 สัปดาห์ | Pending |
| 4 | Development (Frontend + CMS) | 3–5 สัปดาห์ | Pending |
| 5 | Content Population & QA | 1–2 สัปดาห์ | Pending |
| 6 | Launch, Training & Handover | 1 สัปดาห์ | Pending |

---

## รายละเอียดแผนงานทีละขั้น

### เฟส 0: Discovery & Content Archive (เสร็จสิ้นแล้ว)
**วัตถุประสงค์**: เก็บข้อมูลและสินทรัพย์จากเว็บปัจจุบันให้ครบถ้วน

**สิ่งที่ทำไปแล้ว**:
- [x] สร้าง GitHub Repository: `cominnocenter-premium-redesign`
- [x] เก็บข้อความหน้า Home, About, Works
- [x] เก็บโครงสร้างบริการ 9 ด้าน
- [x] เก็บข้อมูลทีมนำและทีมงาน
- [x] เก็บอ้างอิงรูปภาพและโลโก้
- [x] เขียนแนวทางการออกแบบเบื้องต้น (Design Guidelines)
- [x] อัปเดตระบบสีตามอัตลักษณ์จริง (ชมพูจุฬาฯ + น้ำเงินคณะ + SDG)
- [x] สร้าง JSON Database ของเนื้อหา

**Deliverable**: โครงสร้างใน GitHub พร้อมใช้งาน

---

### เฟส 1: Strategy & Design Foundation
**วัตถุประสงค์**: กำหนดทิศทางแบรนด์และระบบออกแบบให้ชัดเจน

**งานที่ต้องทำ**:
1. ยืนยัน Hex Code สีชมพูของจุฬาฯ และสีน้ำเงินของคณะ (ขอจากทางศูนย์)
2. คัดเลือก SDG Goals ที่เกี่ยวข้องกับผลงานของศูนย์มากที่สุด (แนะนำ 4–6 เป้าหมายหลัก)
3. กำหนด Brand Personality และ Tone of Voice ฉบับละเอียด
4. สร้าง Color System ฉบับสมบูรณ์ (Primary, Secondary, Neutral, SDG Accents, Semantic)
5. เลือก Typography (ฟอนต์ไทย + อังกฤษ ที่รองรับสองภาษาสวยและพรีเมียม)
6. กำหนดหลักการใช้โลโก้และสัญลักษณ์
7. สร้าง Moodboard / Visual Direction Board

**Deliverables**:
- Brand Guidelines ฉบับย่อ (PDF หรือ Figma)
- Color Palette + Typography System
- Moodboard

---

### เฟส 2: Information Architecture & Content Strategy
**วัตถุประสงค์**: ออกแบบโครงสร้างเว็บและกลยุทธ์เนื้อหา

**งานที่ต้องทำ**:
1. ออกแบบ Sitemap ฉบับสมบูรณ์
2. กำหนด User Journey หลัก 3–4 กลุ่ม (ภาครัฐ, องค์กรระหว่างประเทศ, บริษัทเอกชน, นักศึกษา/นักวิจัย)
3. เขียน Content Outline ของทุกหน้า
4. กำหนดโครงสร้าง Case Study / Impact Story
5. วางแผนเนื้อหาสองภาษา (Thai Primary + English)
6. กำหนด Priority ของหน้า (MVP vs Phase 2)

**โครงสร้างหน้าเว็บที่แนะนำ**:
- Home
- About the Center
- Leadership & Team
- Expertise / Services (9 บริการ)
- Impact / Our Works (Case Studies)
- Knowledge & Insights
- Collaborate / Contact

**Deliverables**:
- Sitemap
- Content Inventory & Outline
- Wireframe ระดับต่ำ (Low-fidelity) ของหน้าหลัก

---

### เฟส 3: Visual Design (UI/UX + Design System)
**วัตถุประสงค์**: ออกแบบหน้าตาและประสบการณ์ผู้ใช้ระดับพรีเมียม

**งานที่ต้องทำ**:
1. สร้าง Design System ใน Figma (Components, Tokens, Patterns)
2. ออกแบบหน้า Home (Hero + Services + Impact + CTA)
3. ออกแบบหน้า About + Leadership
4. ออกแบบหน้า Services (Template)
5. ออกแบบหน้า Case Study / Impact
6. ออกแบบ Responsive (Desktop → Tablet → Mobile)
7. ออกแบบ Micro-interactions และ Motion guidelines
8. ทำ Prototype แบบคลิกได้ (Interactive Prototype)

**Deliverables**:
- Figma Design System
- High-fidelity Designs ของหน้าหลักทั้งหมด
- Interactive Prototype
- Design Handoff Notes

---

### เฟส 4: Development
**วัตถุประสงค์**: พัฒนาเว็บไซต์ให้สวย เร็ว และดูแลง่าย

**Tech Stack ที่แนะนำ**:
- Frontend: Next.js 15 (App Router) + TypeScript + Tailwind CSS
- Animation: Framer Motion หรือ GSAP
- CMS: Sanity.io หรือ Payload CMS (เพื่อให้ทีมแก้ไขเนื้อหาได้ง่าย)
- Hosting: Vercel
- Image Optimization: Next/Image + Cloudinary

**งานที่ต้องทำ**:
1. ตั้งค่าโปรเจกต์ + Design Tokens
2. พัฒนา Layout และ Navigation
3. พัฒนาหน้า Home
4. พัฒนาหน้า About / Team
5. พัฒนาหน้า Services (Dynamic)
6. พัฒนาหน้า Impact / Case Studies
7. เชื่อม CMS และ Content Models
8. ทำระบบสองภาษา (i18n)
9. Performance Optimization + Accessibility (WCAG 2.2)
10. SEO Technical Setup

**Deliverables**:
- Staging Website
- CMS ที่พร้อมใช้งาน
- เอกสาร Technical

---

### เฟส 5: Content Population, Testing & Refinement
**วัตถุประสงค์**: ใส่เนื้อหาจริงและทดสอบให้สมบูรณ์

**งานที่ต้องทำ**:
1. เขียน/ปรับเนื้อหาจริงทุกหน้า (ไทย + อังกฤษ)
2. ถ่ายภาพ / จัดหาภาพคุณภาพสูงเพิ่มเติม
3. ใส่ Case Studies ที่มีอยู่จริง
4. ทดสอบข้ามเบราว์เซอร์และอุปกรณ์
5. ทดสอบ Accessibility
6. ทดสอบความเร็ว (Core Web Vitals)
7. รับ Feedback จาก Stakeholders และปรับปรุง

**Deliverables**:
- เว็บไซต์ที่เนื้อหาครบและทดสอบแล้ว
- รายงาน QA

---

### เฟส 6: Launch, Training & Handover
**วัตถุประสงค์**: เปิดตัวและส่งมอบอย่างมืออาชีพ

**งานที่ต้องทำ**:
1. เตรียม Domain / DNS / SSL
2. Soft Launch + Final Check
3. Official Launch
4. อบรมทีมในการใช้ CMS
5. ส่งมอบเอกสารทั้งหมด (Design, Content, Technical)
6. วางแผนบำรุงรักษาและอัปเดตในอนาคต

**Deliverables**:
- เว็บไซต์ Live
- คู่มือการใช้งาน CMS
- เอกสาร Handover ครบชุด

---

## ลำดับความสำคัญถัดไป (Immediate Next Steps)

1. **ยืนยัน Hex Code** สีชมพูจุฬาฯ และสีน้ำเงินคณะ
2. **คัดเลือก SDG Goals** หลักที่เกี่ยวข้องกับงานของศูนย์
3. **สร้าง Moodboard + Color System** ฉบับละเอียด
4. **ออกแบบ Sitemap** ฉบับสมบูรณ์
5. **เริ่ม Low-fidelity Wireframes**

---

## หมายเหตุสำคัญ
- ทุกเฟสสามารถปรับได้ตามความพร้อมของข้อมูลและ Feedback
- แนะนำให้ทำงานแบบ Agile (Sprint 1–2 สัปดาห์) เพื่อให้เห็นความคืบหน้าเร็ว
- ไฟล์ทั้งหมดจะถูกเก็บใน GitHub Repository นี้เป็น Single Source of Truth

---

**ผู้รับผิดชอบหลัก**: ทีมออกแบบ + พัฒนา (ร่วมกับ Assoc. Prof. Dr. Smith Boonchutima และทีมศูนย์)

อัปเดตแผนนี้ได้ตลอดเมื่อมีการเปลี่ยนแปลงครับ
