# Enode - Landing Page (Figma to HTML & Tailwind CSS)

Ushbu loyiha Figma dizayni (`https://www.figma.com/design/YQQyj3M2BNUZI5pgrR5nRf/Untitled?node-id=0-1`) asosida **Composio** orqali barcha Figma node-lari, vektorlari, rasmlari va rang kodlari olinib, 1:1 formatda **HTML** va **Tailwind CSS** yordamida to'liq yaratildi. Foydalanuvchi talabiga ko'ra **JavaScript ishlatilmadi** (0 JS).

---

## 🚀 Qanday ochish mumkin?

Loyihani ko'rish uchun hech qanday node_modules, npm yoki server talab qilinmaydi:
1. Brauzerda to'g'ridan-to'g'ri `index.html` faylini oching:
   - Fayl yo'li: `C:\Users\user\enode-landing\index.html`
   - Yoki sichqoncha bilan ikki marta bosing.

---

## 🎨 Loyihaning tuzilishi

```
enode-landing/
│
├── index.html                 # 1:1 Pixel-perfect HTML + Tailwind CSS sahifasi (0 JS)
├── README.md                  # Loyiha qo'llanmasi
└── assets/                    # Figma-dan Composio orqali yuklab olingan barcha rasmlar va grafiklar
    ├── logo.png               # Enode logotipi
    ├── hero-illustration.png  # Hero bo'limi 3D grafikasi
    ├── partner-1.png          # Hamkor Monta logotipi
    ├── partner-2.png          # Hamkor Tibber logotipi
    ├── partner-3.png          # Hamkor TotalEnergies logotipi
    ├── partner-4.png          # Hamkor OVO logotipi
    ├── partner-5.png          # Hamkor E.ON logotipi
    ├── partner-6.png          # Hamkor Good Energy logotipi
    ├── platform-diagram.png   # "With Enode vs Without Enode" arxitektura diagrammasi
    ├── connect-illustration.png   # "Connect" API bo'limi grafikasi
    ├── optimize-illustration.png  # "Optimize" bo'limi grafikasi
    ├── aggregate-illustration.png # "Aggregate" bo'limi grafikasi
    ├── blog-1.png             # Blog post 1 rasmi
    ├── blog-2.png             # Blog post 2 rasmi
    ├── blog-3.png             # Blog post 3 rasmi
    ├── blog-4.png             # Blog post 4 rasmi
    └── cta-illustration.png   # "Ready to get started?" bo'limi grafikasi
```

---

## 📑 Sahifa bo'limlari (1:1 Figma bo'yicha)

1. **Header / Navbar**:
   - Enode logotipi
   - Navigatsiya menyusi: Products, Use cases, Pricing, Company, Developers
   - Dropdown hover menyulari (sof CSS bilan)
   - "Contact sales" havolasi va "Start building" tugmasi

2. **Hero Section**:
   - Asosiy sarlavha: `Infrastructure for green energy apps` (72px)
   - Tavsif matni
   - Ikkita CTA tugma: "Start building" va "Contact sales"
   - Figma-dan olingan 3D abstract yashil energiya render grafikasi

3. **Client Logos Bar**:
   - 6 ta yetakchi energiya brendlari logotiplari (Monta, Tibber, TotalEnergies, OVO, E.ON, Good Energy)

4. **"Our platform" Bo'limi**:
   - `Connect API`, `Optimize`, `Aggregate` bo'yicha 3 ta ustunli tushuntirish
   - "With Enode" va "Without Enode" arxitektura diagrammasi
   - Aloqalar soni ko'rsatkichlari (1 ta mijoz orqali vs 45+ Enode orqali)

5. **"Connect" Bo'limi**:
   - `One powerful API, hundreds of EVs and energy devices`
   - 20+ brendlar, 100+ qurilmalar ro'yxati, "Learn more" havolasi
   - Maxsus Connect illyustratsiyasi

6. **"Optimize" Bo'limi (Alternativ joylashuv)**:
   - `Enable smart energy use cases for your customers`
   - Smart charging va tahlil imkoniyatlari
   - Maxsus Optimize illyustratsiyasi

7. **"Aggregate" Bo'limi**:
   - `Accelerate the transition to a sustainable future`
   - Moslashuvchan talab (demand response) va virtual energiya tarmoqlari
   - Maxsus Aggregate illyustratsiyasi

8. **"By developers, for developers" (Dark mavzu #191610)**:
   - RESTful API, SDKlar va xavfsizlik haqida
   - O'ng tomonda sintaksisi bo'yalgan qora terminal/IDE kodi (Enode API JSON javobi)

9. **"Why Enode" / Statistika**:
   - Kompaniya yutuqlari va nufuzi
   - 4 ta maxsus kartochka:
     - `100+` Energy hardware models supported
     - `60+ million` Energy customers reached (Ajratilgan to'q yashil karta `#0E6400`)
     - `25%` Average savings using Enode's Smart Charging
     - `100GWh+` Managed through the Enode platform

10. **"Use cases"**:
    - 4 ta toifadagi foydalanish holatlari (Smart charging, Energy management, Demand response, E-mobility)

11. **"Industries and applications"**:
    - 8 ta sohaga mo'ljallangan yechimlar kartochkalari

12. **"Latest from the blog"**:
    - So'nggi maqolalar uchun 4 ta blog kartochkasi (teglar, sarlavhalar, xulosalar va rasmlar)

13. **"Ready to get started?" (CTA Banner)**:
    - To'q yashil (`#17290E`) fonli katta CTA karta
    - Boshlash va aloqa tugmalari
    - 3D illyustratsiya

14. **"Lead the transition to open energy" (Newsletter)**:
    - Oylik yangiliklarga obuna bo'lish formasi

15. **Footer**:
    - To'liq sayt xaritasi (Products, Use cases, Developers, Company)
    - Mualliflik huquqi va huquqiy bildirishnoma
