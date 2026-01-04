```
src/
├─ pages/
│   ├─ cars/
│   │   ├─ index.tsx        → /cars
│   │   ├─ [id].tsx         → /cars/42
│   │   └─ create.tsx       → /cars/create
│   │
│   └─ profile/
│       └─ cars.tsx         → /profile/cars
│
├─ components/
│   ├─ ui/
│   │   ├─ Button.tsx
│   │   ├─ Input.tsx
│   │   └─ Select.tsx
│   │
│   ├─ layout/
│   │   ├─ Header.tsx
│   │   └─ PageWrapper.tsx
│   │
│   └─ cars/
│       ├─ CarCard.tsx
│       ├─ CarList.tsx
│       ├─ CarFilters.tsx
│       ├─ CarGallery.tsx
│       └─ CarSpecs.tsx
│
├─ features/
│   └─ cars/
│       ├─ cars.api.ts
│       ├─ cars.service.ts
│       ├─ cars.types.ts
│
├─ hooks/
│   └─ useCars.ts
│
├─ lib/
│   └─ axios.ts


‍‍‍‍‍
my-next-project/
├─ pages/
│   ├─ index.tsx
│   ├─ about.tsx
│   ├─ docs/
│   │   ├─ index.tsx
│   │   ├─ [docId].tsx
│   │   └─ tutorials/
│   │       ├─ index.tsx
│   │       └─ [tutorialId].tsx
│   └─ api/
│       ├─ docs/
│       │   └─ index.ts
│       └─ users/
│           └─ auth.ts
├─ components/
│   ├─ ui/
│   │   ├─ Button.tsx
│   │   ├─ Card.tsx
│   │   └─ Modal.tsx
│   ├─ layout/
│   │   ├─ Header.tsx
│   │   └─ Footer.tsx
│   └─ docs/
│       ├─ DocCard.tsx
│       ├─ DocList.tsx
│       └─ DocViewer.tsx
├─ features/
│   ├─ docs/
│   │   ├─ docs.api.ts
│   │   ├─ docs.service.ts
│   │   └─ docs.types.ts
│   └─ users/
│       ├─ auth.api.ts
│       ├─ auth.service.ts
│       └─ auth.types.ts
├─ hooks/
│   ├─ useDocs.ts
│   └─ useAuth.ts
├─ lib/
│   ├─ axios.ts
│   └─ helpers.ts
├─ styles/
│   └─ globals.css
├─ docs/                     # مستندات کامل پروژه
│   ├─ README.md
│   ├─ setup.md
│   ├─ architecture.md
│   └─ guidelines.md
└─ README.md                 # روت پروژه



my-next-project/
├─ pages/
│   ├─ index.tsx               # صفحه اصلی
│   ├─ about.tsx               # درباره
│   ├─ docs/                   # صفحات مستندات
│   │   ├─ index.tsx           # لیست مستندات
│   │   └─ [docId].tsx         # جزئیات هر مستند
│   └─ api/                    # API routes
│       └─ docs.ts
│
├─ components/
│   ├─ ui/                     # کامپوننت های عمومی
│   │   ├─ Button.tsx
│   │   └─ Card.tsx
│   ├─ layout/                 # Header / Footer / Sidebar
│   └─ docs/                   # کامپوننت های مرتبط با مستندات
│       ├─ DocCard.tsx
│       ├─ DocList.tsx
│       └─ DocViewer.tsx
│
├─ features/
│   └─ docs/
│       ├─ docs.api.ts         # fetch docs
│       ├─ docs.service.ts     # business logic
│       └─ docs.types.ts       # تایپ‌ها
│
├─ hooks/
│   └─ useDocs.ts              # hook برای دریافت مستندات
│
├─ lib/
│   └─ axios.ts
│
├─ styles/
│   └─ globals.css
│
├─ docs/                       # فایل های مستندات اصلی پروژه
│   └─ README.md
│
└─ README.md                   # فایل روت پروژه


```
