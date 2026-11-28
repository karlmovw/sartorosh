# 💈 Barber Cuts — Onlayn Navbat va Barbershop Boshqaruv Tizimi

**Barber Cuts** — erkaklar sartaroshxonasi (Barbershop) uchun ishlab chiqilgan zamonaviy, tezkor va to‘liq avtomatlashtirilgan onlayn bron qilish hamda biznesni boshqarish ekotizimi.

🌐 **Rasmiy sayt:** [SAYT_LINKI_SHU_YERGA]  
🤖 **Telegram Bot & Mini App:** [@sulaymon_cuts_bot](https://t.me/sulaymon_cuts_bot)

---

## ✨ Asosiy imkoniyatlar

### 👤 1. Mijozlar uchun qulayliklar
- **1 daqiqada onlayn navbat olish:** Ustani, bir nechta xizmat turini (masalan, soch + soqol) bir vaqtda tanlash va umumiy vaqt/narxni avtomatik hisoblash.
- **Aqlli bo‘sh vaqtlar:** Ustaning real ish jadvali, tushlik tanaffusi va band qilingan soatlarga qarab faqat bo‘sh vaqtlarni ko‘rsatish.
- **Shaxsiy kabinet (`/client`):** Faol navbatlar, tashriflar tarixi, sevimli ustalar, sharh qoldirish va shaxsiy profilni boshqarish.
- **Avtomatik eslatmalar:** Navbat vaqtiga **1 soat** va **30 daqiqa** qolganda Telegram bot orqali eslatma xabarlari.

### 💈 2. Ustalar (Sartaroshlar) kabineti (`/barber`)
- **Jonli jadval:** Bugungi, ertangi va haftalik mijozlar navbatini tartibli ko‘rish.
- **Moslashuvchan ish grafigi:** Haftalik ish kunlari, ish boshlash/tugash soatlari va tushlik vaqtini mustaqil sozlash (asosiy sayt bilan bir zumda sinxronlanadi).
- **Status va Statistika:** Mijoz tashriflarini tasdiqlash/yakunlash, shaxsiy ish natijalarini galereyaga yuklash va daromad statistikasini kuzatish.

### 🛡️ 3. Admin Boshqaruv Paneli (`/admin`)
- **To‘liq nazorat:** Ustalar, xizmatlar, narxlar, mijozlar bazasi va barcha bronlarni yagona joydan boshqarish.
- **Sayt va Reklama boshqaruvi:** Bosh sahifa bannerlari, aksiya tasmalari, vitrina rasmlari, salon nomi va aloqa ma’lumotlarini kodsiz real vaqtda tahrirlash.
- **Tahlil va Hisobotlar:** Kunlik tushum, eng faol ustalar va mijozlar oqimi statistikasi.

### 🤖 4. 24/7 Telegram Bot & Mini App (`@sulaymon_cuts_bot`)
- **Telegram Mini App:** Saytning barcha imkoniyatlari to‘g‘ridan-to‘g‘ri Telegram ichida ilova sifatida ochiladi.
- **Tezkor kirish:** Telefon raqam ulashish orqali bir bosishda ro‘yxatdan o‘tish va web-kabinet bilan to‘liq sinxronizatsiya.
- **Ustalar uchun bot menyusi:** Yangi bron tushganda tezkor xabar olish hamda `Bugun`, `Ertaga`, `Shu hafta` buyruqlari orqali jadvalni ko‘rish.

### 📱 5. PWA (Mobil ilova sifatida o‘rnatish)
- Telefon (Android / iOS) va kompyuter ekraniga alohida ilova sifatida o‘rnatish imkoniyati (`Service Worker` va `Web App Manifest` bilan).

---

## ⚙️ Texnologik arxitektura
- **Frontend:** HTML5, CSS3 (Dark Void dizayn), Vanilla JavaScript, PWA
- **Backend / Serverless:** Cloudflare Pages Functions (24/7 Edge API & Telegram Webhook)
- **Ma’lumotlar bazasi:** Cloudflare D1 (SQLite)
- **Xavfsizlik:** JWT sessiya nazorati, parollarni `bcryptjs` bilan xeshlash, Telegram WebApp `initData` izolyatsiyasi

---

## 🔗 Havolalar
- 🌐 **Veb-sayt:** https://sulaymon-cuts.pages.dev/
- 🤖 **Telegram Bot:** https://t.me/sulaymon_cuts_bot
