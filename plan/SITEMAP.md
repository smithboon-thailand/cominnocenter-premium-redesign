# Sitemap – ComInnoCenter Premium Website

**อัปเดต**: 13 สิงหาคม 2569  
**สถานะ**: Draft v1 – พร้อมสำหรับการออกแบบ Wireframe

---

## โครงสร้างหลัก (Primary Navigation)

```
Home
├── About
│   ├── The Center (Mission / Vision / Objectives)
│   ├── Leadership
│   └── Our Team
├── Expertise (Services)
│   ├── Book & Printing
│   ├── Motion Effect & AR
│   ├── Video Production
│   ├── Training
│   ├── Research & Evaluation
│   ├── Communication Design
│   ├── Campaign Management
│   ├── Seminar
│   └── Marketing Event
├── Impact (Our Works)
│   ├── All Projects
│   ├── Filter by Service
│   ├── Filter by SDG
│   └── Individual Case Study pages
├── Knowledge
│   ├── Publications & E-Books
│   ├── Insights / Articles
│   └── Media Coverage
└── Collaborate
    ├── Partnership Opportunities
    ├── Request Training / Seminar
    └── Contact Us
```

---

## รายละเอียดแต่ละหน้า

### 1. Home (`/`)
**วัตถุประสงค์**: สร้างความประทับใจแรก + สื่อสาร Impact + ชวนให้ Collaborate

**Sections แนะนำ**:
- Hero (Cinematic + Tagline “Communication Innovation for a Better Life”)
- The Center in brief + Key numbers / Impact highlights
- Selected Services (3–4 บริการเด่น)
- Featured Case Studies / Impact Stories
- Leadership highlight
- Partners / Clients logo wall
- Call-to-Action หลัก (Collaborate with us)

**Priority**: MVP (สูงสุด)

---

### 2. About (`/about`)

#### 2.1 The Center (`/about`)
- Mission, Vision, 3 Objectives
- Story of the Center
- How we work (Research → Innovation → Impact)

#### 2.2 Leadership (`/about/leadership`)
- Profile ของ Head และ Deputy Heads (Smith Boonchutima, Teerada, Pavel)
- Education + Selected works

#### 2.3 Our Team (`/about/team`)
- Grid ของทีมทั้งหมด (Faculty + Researchers + Assistants + Designer)
- Filter ได้ตามบทบาท (ถ้าต้องการ)

**Priority**: MVP

---

### 3. Expertise / Services (`/expertise`)

หน้า Overview + หน้าย่อยของแต่ละบริการ (9 หน้า)

| Service | Suggested URL |
|---------|---------------|
| Book & Printing | `/expertise/book-printing` |
| Motion Effect & AR | `/expertise/ar-motion` |
| Video Production | `/expertise/video-production` |
| Training | `/expertise/training` |
| Research & Evaluation | `/expertise/research-evaluation` |
| Communication Design | `/expertise/communication-design` |
| Campaign Management | `/expertise/campaign` |
| Seminar | `/expertise/seminar` |
| Marketing Event | `/expertise/marketing-event` |

**โครงสร้างหน้า Service แต่ละหน้า**:
- Hero + Short description
- What we deliver
- Our Process
- Related Case Studies
- CTA: Inquire about this service

**Priority**: MVP (Overview + 4–5 บริการหลักก่อนได้)

---

### 4. Impact / Our Works (`/impact`)

- หน้า Listing พร้อม Filter (Service / SDG / Year)
- หน้า Case Study แต่ละชิ้น (`/impact/[slug]`)

**โครงสร้าง Case Study แนะนำ**:
- Challenge
- Approach / Our Role
- Outcome & Impact
- Related SDGs
- Gallery / Video
- Testimonial (ถ้ามี)

**Priority**: MVP (Listing + 5–8 Case Studies แรก)

---

### 5. Knowledge (`/knowledge`)

- Publications & E-Books
- Insights / Articles / Blog
- Media Coverage / News

**Priority**: Phase 2 (สามารถเริ่มด้วยหน้าเดียวรวมก่อน)

---

### 6. Collaborate (`/collaborate`)

- Partnership Opportunities
- Request for Training / Seminar / Research
- Contact Form + ข้อมูลติดต่อ
- Map / Location (ถ้าต้องการ)

**Priority**: MVP

---

## Secondary / Utility Pages

- Privacy Policy
- Terms of Use (ถ้าจำเป็น)
- 404 Page
- Language Switcher (TH / EN)

---

## แนะนำ URL Structure (Clean & SEO-friendly)

```
/                          → Home
/about                     → The Center
/about/leadership          → Leadership
/about/team                → Team
/expertise                 → Services Overview
/expertise/[service]       → Individual Service
/impact                    → All Works
/impact/[project-slug]     → Case Study
/knowledge                 → Knowledge Hub
/collaborate               → Collaborate / Contact
```

---

## MVP Scope แนะนำ (Phase 1 Launch)

1. Home
2. About (The Center + Leadership + Team)
3. Expertise Overview + 5 บริการหลัก
4. Impact Listing + 6–8 Case Studies
5. Collaborate / Contact

**Phase 2** เพิ่ม:
- บริการที่เหลือ
- Knowledge section เต็มรูปแบบ
- Filter ขั้นสูง
- ระบบค้นหา

---

## หมายเหตุสำหรับ Wireframe

- Navigation ควรคงที่และชัดเจน
- Mobile: ใช้ Hamburger + ลำดับที่สำคัญก่อน
- ทุกหน้าควรมี CTA ที่ชัดเจนไปยัง Collaborate หรือ Service ที่เกี่ยวข้อง

---

**ไฟล์นี้พร้อมสำหรับการนำไปออกแบบ Low-fidelity Wireframes ต่อได้เลย**
