<div align="center">

# مؤسسة غزارة للتجارة والتسويق | Ghazara Enterprise Platform

**البنية التحتية الرقمية لإدارة المبيعات، سندات التبرعات، الطلبات، وعمولات المسوّقين**  
*Enterprise Sales, Request Management, Donation Bonds Verification & Marketer Commissions Engine*

[![Location](https://img.shields.io/badge/Location-Hadramaut%2C%20Yemen%20%F0%9F%87%BE%F0%9F%87%AA-0D9488?style=for-the-badge)](https://ghazara.net)
[![Website](https://img.shields.io/badge/Website-ghazara.net-1E40AF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ghazara.net)
[![Next.js](https://img.shields.io/badge/Next.js-14%2B%20(App%20Router)-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%2B-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![Sentry](https://img.shields.io/badge/Sentry-Observability-362D59?style=for-the-badge&logo=sentry&logoColor=white)](https://sentry.io/)
[![RTL Supported](https://img.shields.io/badge/RTL-Arabic%20First%20(dir%3D%22rtl%22)-16A34A?style=for-the-badge)](#localization--regional-standards)
[![License](https://img.shields.io/badge/License-Proprietary-B91C1C?style=for-the-badge)](#license--ownership)

[الموقع الرسمي](https://ghazara.net) · [عن المنصة](#-overview--business-vision-عن-المنصة) · [المميزات](#-core-features-المميزات-الرئيسية) · [البنية التقنية](#-tech-stack--system-architecture) · [دليل التشغيل](#-getting-started--local-setup-دليل-التشغيل)

</div>

---

## 📖 Overview & Business Vision (عن المنصة)

**مؤسسة غزارة للتجارة والتسويق (Ghazara for Trading and Marketing)** — ومقرها الرئيسي في **حضرموت، اليمن** تحت مظلة **بيت التمكين للتسويق (Beit Al-Tamkeen for Marketing)** — تعتمد على هذه المنصة كعمود فقري رقمي لإدارة عملياتها التجارية والتسويقية ومبادراتها التنموية عبر اليمن.

صُممت المنصة لتوحيد دورة العمل بالكامل في بيئة مؤسسية عالية الموثوقية: بدءاً من استقبال طلبات العملاء والجمعيات الخيرية، مروراً بالتحقق المالي من **سندات التبرعات** وتخصيص التراخيص الرقمية دون الحاجة لمخزون مادي، وصولاً إلى **أتمتة احتساب عمولات المسوّقين** ومراقبة صرفها بدقة محاسبية كاملة.

### Localization & Regional Standards

- **واجهة عربية أصلية (`dir="rtl"`):** تجربة مستخدم مصممة من الأساس لدعم اللغة العربية واتجاه العرض من اليمين إلى اليسار.
- **العملات المحلية والإقليمية:** دعم كامل للتعامل بالريال السعودي (`SAR`) والعملات المحلية المعتمدة في التقارير والفواتير والعمولات.
- **التوقيت القياسي (`GMT+3`):** توحيد الطوابع الزمنية لكافة المعاملات المالية، السندات، وسجلات التدقيق وفق توقيت اليمن والمملكة العربية السعودية (`Asia/Aden` / `UTC+3`).

---

## ✨ Core Features (المميزات الرئيسية)

### 1. إدارة المبيعات والتبرعات (Sales & Donation Bonds)
- تتبع متكامل لدورة حياة الطلبات وأوامر المبيعات من الإنشاء وحتى الاعتماد النهائي.
- وحدة متخصصة للتحقق من **سندات التبرعات (Donation Bonds)** المرفوعة من الجمعيات الخيرية والعملاء، مع ربط كل سند بحالته المالية والمرجعية لمنع الازدواجية وضمان الشفافية.

### 2. حساب عمولات المسوقين (Automated Commissions Engine)
- محرك آلي لاحتساب عمولات المسوّقين بناءً على الطلبات المكتملة والمعتمدة مالياً.
- لوحة متابعة دقيقة لحالات الصرف (قيد المراجعة، مستحق، تم الصرف) مع سجل تاريخي للمستحقات.

### 3. إدارة التراخيص والطلبات (Inventory-less License Allocation)
- نموذج تشغيل مرن لتخصيص وتتبع التراخيص الرقمية والطلبات دون الارتباط بمستودعات مادية تقليدية.
- ربط تلقائي بين الطلب المعتمد، الجهة المستفيدة، وحالة تفعيل الترخيص.

### 4. الصلاحيات والحوكمة (Role-Based Access Control - RBAC)
نظام صلاحيات صارم يضمن فصل المهام (Separation of Duties) عبر أربعة أدوار رئيسية:

| الدور الوظيفي | Role Key | نطاق الصلاحيات والمسؤوليات |
| :--- | :--- | :--- |
| **المشرف العام** | `Super Admin` | إدارة كاملة للنظام، الإعدادات العامة، المستخدمين، وسجلات الحوكمة. |
| **مدير المبيعات** | `Sales Manager` | الإشراف على الطلبات، متابعة فرق التسويق، واعتماد العمليات التشغيلية. |
| **المسوّق** | `Marketer` | إنشاء الطلبات، متابعة حالة العملاء، ومراقبة العمولات المستحقة. |
| **المحاسب** | `Accountant` | مراجعة واعتماد سندات التبرعات، التدقيق المالي، وإدارة صرف العمولات. |

### 5. الدعم المحلي واللغوي (Arabic-First & RTL Experience)
- تصميم متجاوب بالكامل (`Responsive RTL`) يعمل بسلاسة على أجهزة سطح المكتب والأجهزة اللوحية والهواتف.
- تنسيق الأرقام، التواريخ (`GMT+3`)، والعملات (`SAR` / العملة المحلية) بما يتوافق مع المعايير المحاسبية في السوق اليمني والخليجي.

---

## 🏗️ Tech Stack & System Architecture

### Technology Matrix

| الطبقة (Layer) | التقنية المستخدمة | الدور في المنصة |
| :--- | :--- | :--- |
| **Frontend** | **Next.js 14+ (App Router)**, **React**, **TypeScript** | بناء الواجهات التفاعلية، Server Components، والتوجيه المتقدم. |
| **Styling & UI** | **Tailwind CSS** (`dir="rtl"`) | تصميم واجهة عربية عصرية سريعة الاستجابة مع دعم RTL أصيل. |
| **Backend & API** | **Next.js Route Handlers & Server Actions** | منطق الأعمال، التحقق من الصلاحيات (RBAC)، ومحرك العمولات. |
| **ORM** | **Prisma ORM** | نمذجة البيانات، كتابة الاستعلامات الآمنة نوعياً (Type-safe)، وإدارة الترحيلات. |
| **Database** | **PostgreSQL** | تخزين موثوق للطلبات، سندات التبرعات، التراخيص، وسجلات العمولات. |
| **Observability** | **Sentry** | تتبع الأخطاء في الوقت الفعلي ومراقبة أداء الخادم والواجهة. |

### High-Level Data Flow

```text
┌──────────────────────────┐
│   Client Browser (RTL)   │  ──▶  Next.js 14+ App Router (UI / Server Actions / API Routes)
└──────────────────────────┘                     │
                                                 ▼
                                   RBAC & Validation Layer (TypeScript)
                                                 │
                                                 ▼
                                           Prisma ORM
                                                 │
                                                 ▼
                                      PostgreSQL Database
                                                 │
                              ┌──────────────────┴──────────────────┐
                              ▼                                     ▼
                    Sentry Error Tracking                 GMT+3 Audit & Reporting
```

1. **الطلب (Request):** يتفاعل المستخدم عبر واجهة عربية (`dir="rtl"`) مبنية بـ Next.js App Router وTailwind CSS.
2. **التحقق والحوكمة (Authorization & Validation):** تمر الطلبات عبر طبقة التحقق من الهوية والصلاحيات (`Super Admin`, `Sales Manager`, `Marketer`, `Accountant`).
3. **طبقة البيانات (Data Layer):** يتولى **Prisma ORM** تنفيذ العمليات والمعاملات (Transactions) لضمان اتساق البيانات المالية وسندات التبرعات.
4. **التخزين والمراقبة (Persistence & Monitoring):** تُحفظ البيانات في **PostgreSQL** بتوقيت `GMT+3`، بينما يلتقط **Sentry** أي استثناءات أو تباطؤ في الأداء بشكل فوري.

---

## 🚀 Getting Started & Local Setup (دليل التشغيل)

اتبع الخطوات التالية لتشغيل بيئة التطوير المحلية على جهازك.

### Prerequisites (المتطلبات الأساسية)

- **Node.js**: الإصدار `18.x` أو أحدث (`v20 LTS` موصى به)
- **PostgreSQL**: الإصدار `15` أو أحدث (أو عبر Docker)
- **Package Manager**: `npm` أو `pnpm`
- **Git**: لإدارة النسخ واستنساخ المستودع

### Installation Steps (خطوات التثبيت)

#### 1. استنساخ المستودع (Clone the Repository)

```bash
git clone https://github.com/muin-sa/ghazara-platform.git
cd ghazara-platform
```

#### 2. تثبيت الحزم البرمجية (Install Dependencies)

```bash
npm install
# أو باستخدام pnpm
pnpm install
```

#### 3. إعداد متغيرات البيئة (Environment Variables)

انسخ ملف البيئة النموذجي وقم بتحديث القيم الخاصة ببيئتك المحلية:

```bash
cp .env.example .env
```

قم بتعبئة المتغيرات التالية داخل ملف `.env`:

| المتغير | الوصف | مثال |
| :--- | :--- | :--- |
| `DATABASE_URL` | رابط الاتصال بقاعدة بيانات PostgreSQL | `postgresql://postgres:postgres@localhost:5432/ghazara_db?schema=public` |
| `AUTH_SECRET` | مفتاح التشفير الخاص بالجلسات والمصادقة | سلسلة عشوائية آمنة (`openssl rand -base64 32`) |
| `NEXT_PUBLIC_APP_URL` | الرابط الأساسي للتطبيق | `http://localhost:3000` |
| `TZ` | المنطقة الزمنية للنظام | `Asia/Aden` (`GMT+3`) |
| `SENTRY_DSN` | رابط مشروع Sentry لتتبع الأخطاء (اختياري محلياً) | `https://examplePublicKey@o0.ingest.sentry.io/0` |
| `NEXT_PUBLIC_DEFAULT_CURRENCY` | رمز العملة الافتراضية | `SAR` |

#### 4. تهيئة قاعدة البيانات (Database & Prisma Setup)

تأكد من تشغيل خادم PostgreSQL، ثم نفّذ أوامر Prisma لإنشاء الجداول وتوليد العميل:

```bash
# توليد Prisma Client
npx prisma generate

# تطبيق الترحيلات على قاعدة البيانات
npx prisma migrate dev

# (اختياري) تعبئة البيانات الأولية والأدوار الافتراضية
npx prisma db seed
```

#### 5. تشغيل خادم التطوير (Start Development Server)

```bash
npm run dev
# أو
pnpm dev
```

افتح المتصفح على الرابط: [http://localhost:3000](http://localhost:3000)

---

## 🛠️ Available Scripts (الأوامر المتاحة)

| الأمر | الوصف |
| :--- | :--- |
| `npm run dev` | تشغيل خادم التطوير المحلي مع Hot Reload |
| `npm run build` | بناء نسخة الإنتاج والتحقق من الأنواع (TypeScript) |
| `npm run start` | تشغيل نسخة الإنتاج بعد البناء |
| `npm run lint` | فحص جودة الكود باستخدام ESLint |
| `npx prisma studio` | فتح واجهة مرئية لاستعراض وتعديل بيانات PostgreSQL |
| `npx prisma migrate deploy` | تطبيق الترحيلات في بيئة الإنتاج |

---

## 🚢 Production Deployment Considerations (النشر والإنتاج)

- **ترحيل قاعدة البيانات:** احرص دائماً على تنفيذ `npx prisma migrate deploy` قبل تشغيل الحزمة الجديدة في بيئة الإنتاج.
- **ضبط المنطقة الزمنية:** تأكد من ضبط `TZ=Asia/Aden` على مستوى الحاوية أو الخادم لضمان تطابق الحسابات اليومية وتقارير العمولات مع توقيت `GMT+3`.
- **المراقبة عبر Sentry:** فعّل متغيرات `SENTRY_DSN` و`SENTRY_AUTH_TOKEN` في خط أنابيب النشر (CI/CD) لرفع Source Maps ومراقبة أخطاء الإنتاج.

---

## 📄 License & Ownership

جميع الحقوق محفوظة © **مؤسسة غزارة للتجارة والتسويق (Ghazara for Trading and Marketing)** — **حضرموت، اليمن**  
تحت مظلة **بيت التمكين للتسويق (Beit Al-Tamkeen for Marketing)**.

- **الموقع الرسمي:** [https://ghazara.net](https://ghazara.net)
- **الحساب التقني على GitHub:** [https://github.com/muin-sa](https://github.com/muin-sa)
