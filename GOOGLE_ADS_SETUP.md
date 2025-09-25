# คู่มือการตั้งค่า Google Ads สำหรับเว็บไซต์ วายเคเอ็น ออโตโมทีฟ

## 🎯 **ขั้นตอนการตั้งค่าสำหรับ Google Ads**

### 1. **แก้ไข Google Analytics ID**
```html
<!-- ในไฟล์ index.html แก้ไขบรรทัดที่ 1071 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
```
เปลี่ยน `G-XXXXXXXXXX` เป็น Google Analytics ID จริงของคุณ

### 2. **ตั้งค่า Google Ads Conversion Tracking**
```html
<!-- ในไฟล์ index.html แก้ไขบรรทัดที่ 1100 และ 1113 -->
'send_to': 'AW-XXXXXXXXX/XXXXXXXXXXXXX'
```
เปลี่ยนเป็น Google Ads Conversion ID และ Conversion Label จริงของคุณ

### 3. **อัปเดต Domain URL**
```html
<!-- แก้ไข URL ใน meta tags และ structured data -->
<meta property="og:url" content="https://your-domain.com">
<link rel="canonical" href="https://your-domain.com">
```

## 📊 **Conversion Actions ที่ติดตาม**

### Phone Call Conversions
- **Header Phone Button**: `header_phone`
- **Floating Call Button**: `floating_call_button`

### Line Click Conversions
- **Header Line Button**: `header_line`
- **Floating Line Button**: `floating_line_button`

### CTA Button Conversions
- **Hero CTA Button**: `hero_cta`

## 🎨 **Google Ads Campaign Recommendations**

### 1. **Search Campaign Keywords**
```
- เคาะพ่นสีรถยนต์
- รับซ่อมตัวถังรถ
- พ่นสีรถยนต์
- เคาะตัวถังรถ
- ซ่อมรถยนต์
- ราคาเคาะพ่นสี
- รับซ่อมรถ
- บริการซ่อมรถ
```

### 2. **Display Campaign Targeting**
- **Demographics**: อายุ 25-65 ปี
- **Interests**: รถยนต์, ซ่อมรถ, ออโตโมทีฟ
- **Geographic**: กรุงเทพมหานคร และปริมณฑล
- **Placements**: เว็บไซต์เกี่ยวกับรถยนต์, ซ่อมรถ

### 3. **YouTube Campaign**
- **Keywords**: "ซ่อมรถ", "เคาะพ่นสี", "พ่นสีรถยนต์"
- **Placements**: ช่องรีวิวรถยนต์, ช่องซ่อมรถ
- **Demographics**: ผู้ชาย 25-55 ปี

## 📱 **Mobile Optimization**

เว็บไซต์ได้รับการปรับแต่งให้เหมาะสำหรับมือถือแล้ว:
- ✅ Responsive Design
- ✅ Fast Loading
- ✅ Mobile-Friendly Navigation
- ✅ Touch-Friendly Buttons
- ✅ Floating Action Buttons

## 🔧 **Performance Optimization**

### Core Web Vitals
- ✅ **LCP**: Optimized images and fonts
- ✅ **FID**: Minimal JavaScript
- ✅ **CLS**: Stable layout

### SEO Optimization
- ✅ **Structured Data**: AutomotiveBusiness schema
- ✅ **Meta Tags**: Complete SEO meta tags
- ✅ **Local SEO**: Geographic targeting
- ✅ **Mobile-First**: Responsive design

## 📈 **Tracking & Analytics**

### Google Analytics 4 Events
- `page_view`: การดูหน้าเว็บ
- `phone_call`: การคลิกโทรศัพท์
- `line_click`: การคลิกไลน์
- `cta_click`: การคลิกปุ่ม CTA
- `form_submit`: การส่งฟอร์มติดต่อ

### Google Ads Conversions
- Phone call conversions
- Line click conversions
- Form submission conversions

## 🚀 **Launch Checklist**

### ก่อนเปิด Google Ads Campaign
- [ ] แก้ไข Google Analytics ID
- [ ] แก้ไข Google Ads Conversion IDs
- [ ] อัปเดต Domain URL
- [ ] ทดสอบ conversion tracking
- [ ] ทดสอบ mobile experience
- [ ] ตรวจสอบ page speed
- [ ] ตั้งค่า Google Search Console

### หลังเปิด Campaign
- [ ] ตรวจสอบ conversion tracking
- [ ] ตรวจสอบ Google Analytics
- [ ] ตรวจสอบ Google Ads reports
- [ ] ตรวจสอบ mobile performance
- [ ] ตรวจสอบ user experience

## 📞 **Contact Information**

- **Phone**: 081-234-5678
- **Email**: info@yknautomotive.com
- **Line**: @yknautomotive
- **Address**: 25/346 ซอยรามคำแหง 124 แขวงสะพานสูง เขตสะพานสูง กรุงเทพมหานคร

## 🎯 **Expected Performance**

### Conversion Rates (Industry Average)
- **Phone Calls**: 3-5%
- **Line Clicks**: 2-4%
- **Form Submissions**: 1-3%

### Cost Per Acquisition (CPA)
- **Phone Calls**: 200-500 บาท
- **Line Clicks**: 150-400 บาท
- **Form Submissions**: 100-300 บาท

---

**หมายเหตุ**: แก้ไขข้อมูล placeholder ทั้งหมดก่อนเปิดใช้งาน Google Ads Campaign
