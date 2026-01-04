```
my-next-project/
├─ pages/
│   ├─ index.tsx                  # صفحه اصلی
│   ├─ about.tsx                  # درباره پروژه
│   ├─ cars/                      # صفحات فروش خودرو
│   │   ├─ index.tsx              # لیست خودروها → /cars
│   │   ├─ [id].tsx               # جزئیات خودرو → /cars/42
│   │   └─ create.tsx             # صفحه ثبت خودرو → /cars/create
│   └─ api/                       # API routes
│       ├─ cars.ts                # API داخلی خودرو
│       └─ users.ts               # API داخلی کاربران
│
├─ components/                    # کامپوننت‌های reusable
│   ├─ ui/                        # کامپوننت عمومی
│   │   ├─ Button.tsx
│   │   ├─ Input.tsx
│   │   └─ Card.tsx
│   ├─ layout/                    # Header / Footer / PageWrapper
│   │   ├─ Header.tsx
│   │   └─ Footer.tsx
│   └─ cars/                      # کامپوننت مربوط به feature خودرو
│       ├─ CarCard.tsx
│       ├─ CarList.tsx
│       ├─ CarFilters.tsx
│       └─ CarGallery.tsx
│
├─ features/                      # منطق feature-based
│   ├─ cars/
│   │   ├─ cars.api.ts            # fetch cars
│   │   ├─ cars.service.ts        # business logic خودرو
│   │   └─ cars.types.ts          # تایپ خودرو
│   └─ users/
│       ├─ auth.api.ts            # login/logout
│       ├─ auth.service.ts
│       └─ auth.types.ts
│
├─ hooks/
│   ├─ useCars.ts                 # hook مخصوص fetch خودروها
│   └─ useAuth.ts
│
├─ lib/
│   ├─ axios.ts                   # axios instance
│   └─ helpers.ts                 # توابع کمکی عمومی
│
├─ styles/
│   └─ globals.css
│
├─ docs/                           # مستندات پروژه
│   ├─ README.md
│   ├─ setup.md
│   ├─ architecture.md
│   └─ guidelines.md
│
└─ README.md                       # روت پروژه


# ساختار پروژه BotoFood

components/                       # تمام کامپوننت‌های reusable
├─ ui/                             # کامپوننت عمومی و قابل استفاده در کل پروژه
│   ├─ Button.tsx                  # دکمه استاندارد
│   ├─ Input.tsx                   # فیلد ورودی
│   └─ Card.tsx                    # کارت اطلاعات (مثلاً محصول یا سفارش)
│
├─ layout/                         # کامپوننت‌های layout ثابت صفحات
│   ├─ Header.tsx                  # هدر سایت
│   └─ Footer.tsx                  # فوتر سایت
│
├─ cart/                            # کامپوننت‌های مربوط به سبد خرید
│   ├─ CartItem.tsx                # نمایش آیتم سبد خرید
│   ├─ CartList.tsx                # لیست همه آیتم‌های سبد
│   └─ CartSummary.tsx             # جمع کل و خلاصه سبد خرید
│
└─ product/                         # کامپوننت‌های مربوط به محصولات
    ├─ ProductCard.tsx             # کارت هر محصول
    ├─ ProductList.tsx             # لیست محصولات
    └─ ProductDetail.tsx           # جزئیات محصول

pages/                              # صفحات سایت (Page Router)
├─ index.tsx                        # صفحه اصلی
├─ about.tsx                        # درباره پروژه
├─ cart.tsx                         # صفحه سبد خرید
├─ products/                        # صفحات محصولات
│   ├─ index.tsx                    # لیست محصولات → /products
│   └─ [id].tsx                     # جزئیات محصول → /products/42
└─ api/                             # API routes داخلی
    ├─ cart.ts                      # API مربوط به سبد خرید
    └─ products.ts                  # API مربوط به محصولات

features/                           # منطق feature-based (business logic)
├─ cart/
│   ├─ cart.api.ts                  # API calls برای سبد خرید
│   ├─ cart.service.ts              # Business logic سبد خرید
│   └─ cart.types.ts                # تایپ‌ها و interface های سبد خرید
│
└─ products/
    ├─ products.api.ts              # API calls برای محصولات
    ├─ products.service.ts          # Business logic محصولات
    └─ products.types.ts            # تایپ‌ها و interface های محصول

hooks/                               # Custom React hooks
├─ useCart.ts                        # مدیریت state سبد خرید
└─ useProducts.ts                    # مدیریت state محصولات

lib/                                 # ابزارهای کمکی
├─ axios.ts                           # axios instance
└─ helpers.ts                         # توابع کمکی عمومی

styles/
└─ globals.css                        # CSS کلی پروژه

public/                               # فایل‌های static (عکس، لوگو و ...)
README.md                              # معرفی پروژه و راهنمای سریع

```


