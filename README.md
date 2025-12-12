<div align="center">

<h1>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&pause=1000&color=3B82F6&center=true&vCenter=true&width=700&lines=Hi+there!+%F0%9F%91%8B+I'm+Ihza+Mahendra;Full+Stack+Developer;Laravel+%7C+Next.js+%7C+React;Building+Scalable+Web+Solutions;Open+to+Opportunities!" alt="Typing SVG" />
</h1>

</div>

---

## 👨‍💻 About Me

I'm a **Full Stack Developer** from Pontianak, Indonesia, specializing in modern web technologies and e-commerce solutions. I build scalable, user-centric applications that solve real business problems.

- 🔭 Currently working on: **Dua Insan Story** - A hybrid e-commerce platform for digital & print invitations
- 🌱 Currently learning: **Advanced Next.js patterns, Cloud Architecture with AWS, Queue Systems**
- 💼 **Open to:** Freelance projects, Full-time opportunities, and Collaborations
- 📍 Based in: Pontianak, Indonesia 🇮🇩
- ⚡ Passionate about: Building performant web applications with excellent UX

---

## 🚀 Featured Project: Dua Insan Story

> **Platform Undangan Cetak dan Digital Terbaik di Pontianak**  
> A comprehensive hybrid e-commerce solution for digital and print wedding invitations

<div align="center">

[![User Site](https://img.shields.io/badge/User_Site-Live-success?style=for-the-badge&logo=vercel)](https://duainsanstory.eproject.tech)
[![Admin Panel](https://img.shields.io/badge/Admin_Panel-Live-success?style=for-the-badge&logo=vercel)](https://admin.duainsanstory.eproject.tech)
[![API Status](https://img.shields.io/badge/API-Running-success?style=for-the-badge&logo=laravel)](https://github.com/ihza6661/dua_insan_story)

</div>

### 🎯 Problem & Solution

**Problem:** Traditional invitation businesses struggle to manage both digital and physical product sales with automated digital activation, payment processing, and order management.

**Solution:** A fully integrated platform with three separate applications:
- **REST API Backend** for centralized business logic
- **Admin Dashboard** for efficient business management
- **Customer Website** for seamless shopping experience

### 🌐 Live Demo & Repositories

| Application | Live Demo | Repository |
|------------|-----------|------------|
| 👥 **User Site** | [duainsanstory.eproject.tech](https://duainsanstory.eproject.tech) | [View Code](https://github.com/ihza6661/duainsan.story-user-site.git) |
| 🛠️ **Admin Panel** | [admin.duainsanstory.eproject.tech](https://admin.duainsanstory.eproject.tech) | [View Code](https://github.com/ihza6661/dua_insan_story_admin.git) |
| ⚙️ **REST API** | Private | [View Code](https://github.com/ihza6661/dua_insan_story.git) |

### 🏗️ System Architecture

```
                    ┌─────────────────────────┐
                    │   Customer Website      │
                    │   (Vite + React 18)     │
                    │   TypeScript + Tailwind │
                    └───────────┬─────────────┘
                                │
                    ┌───────────▼─────────────┐
                    │   Admin Dashboard       │
                    │   (Next.js 15 + React)  │
                    │   TypeScript + Tailwind │
                    └───────────┬─────────────┘
                                │
                    ┌───────────▼─────────────┐      ┌──────────────┐
                    │   REST API Backend      │◄────►│   MySQL      │
                    │   (Laravel 12 + PHP)    │      │   (55 tables)│
                    │   3,540+ lines service  │      └──────────────┘
                    └───────────┬─────────────┘
                                │                     ┌──────────────┐
                                └────────────────────►│   Redis      │
                                  Queue System         │   (Jobs/Cache)
                                  (Email, Notifications)└─────────────┘
                                
    ┌────────────────┬──────────────────┬──────────────────┐
    │   Midtrans     │   RajaOngkir     │   AWS S3         │
    │   Payment      │   Shipping       │   File Storage   │
    └────────────────┴──────────────────┴──────────────────┘
```

### ✨ Key Features

#### 🛒 **Hybrid E-commerce Engine**
- Physical product sales with **customizable attributes** (size, color, material)
- Digital invitation templates with **automatic activation after payment**
- **Multiple product variants** with independent pricing and images
- **Product add-ons system** for upselling
- Advanced **inventory management** with stock tracking
- **Guest checkout** and authenticated user checkout

#### 💳 **Payment & Checkout**
- **Midtrans payment gateway** integration (15+ payment methods)
- **Down payment (DP) system** - 30% minimum
- **Final payment** option for partially paid orders
- **Payment retry** for failed transactions
- **Webhook integration** with signature verification
- **RajaOngkir shipping** integration (JNE, POS, TIKI)
- Real-time **shipping cost calculation**

#### 📧 **Digital Invitation System** 
*The crown jewel of the platform*
- **12-month validity period** with auto-expiry
- **Dynamic form builder** with 9 field types
- **Visual validation rules** configuration
- **Automatic activation** after payment completion
- **Photo upload management** (multiple images)
- **Public sharing** via unique URL
- **View count tracking**
- **Email notification** with activation link
- **Multiple template designs** (Classic, Sakeena, etc.)

#### 🎨 **Design Proof System**
- Admin uploads design proofs for custom orders
- Customer **review workflow** (Approve/Revision/Reject)
- **Version tracking** with history
- **Email notifications** for both parties
- Seamless integration with order management

#### 📦 **Order Management**
- **13 order statuses** with automated workflows
- **Order cancellation system** with 24-hour window
- Admin **approval/rejection workflow** for cancellations
- **Refund processing** via Midtrans API
- **Order tracking** with visual timeline
- **Invoice generation** (PDF download)
- **Activity logging** for audit trail

#### ⭐ **Review & Rating System**
- **5-star rating** with photo uploads (up to 5 images)
- **Review moderation** (admin approval)
- **Featured reviews** system
- **Admin responses** to reviews
- **Helpful vote** system
- **Verified purchase** badge
- Rate limiting: 5 reviews per hour

#### 🎁 **Promo Code System**
- **Percentage** and **fixed amount** discounts
- Minimum purchase requirements
- Usage limits (total & per user)
- Start/end date validity
- Usage tracking and statistics

#### 🔔 **Notification System**
- **12 automated email templates**
- In-app notifications with unread badge
- **Laravel Queues** for async processing
- Email notifications for: orders, payments, design proofs, cancellations

#### 📊 **Admin Analytics Dashboard**
- Revenue tracking with **trend charts**
- Order status **distribution charts**
- **Top 5 products** widget
- **Low stock alerts** (< 10 items)
- Customer count & growth metrics
- Cancellation rate tracking
- Date range filters (daily, weekly, monthly, custom)

### 🛠️ Complete Tech Stack

#### **Backend (Laravel API)**

<div align="center">

![PHP](https://img.shields.io/badge/PHP_8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-D82C20?style=for-the-badge&logo=redis&logoColor=white)
![Sanctum](https://img.shields.io/badge/Laravel_Sanctum-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white)

</div>

**Key Packages:**
- `laravel/sanctum` ^4.0 - JWT Authentication
- `midtrans/midtrans-php` ^2.6 - Payment gateway
- `guzzlehttp/guzzle` ^7.9 - HTTP client (RajaOngkir API)
- `barryvdh/laravel-dompdf` ^3.1 - PDF generation
- `league/flysystem-aws-s3-v3` ^3.0 - AWS S3 integration
- `phpunit/phpunit` ^11.5 - Testing framework

**Architecture:**
- Repository-Service-Controller pattern
- 33 Eloquent models
- 30+ service classes (3,540+ lines)
- 55 database tables
- 55 migrations with seeders
- 20+ feature tests (118+ assertions)

#### **Admin Dashboard (Next.js)**

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript_5-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)

</div>

**Key Libraries:**
- `@tanstack/react-query` ^5.84 - Server state management
- `zustand` ^5.0 - Client state management
- `react-hook-form` ^7.62 - Form handling
- `zod` ^4.0 - Schema validation
- `shadcn/ui` - 28 UI components
- `@radix-ui/*` - Accessible primitives
- `recharts` ^3.3 - Data visualization
- `next-themes` ^0.4 - Dark mode support

**Features:**
- 50+ admin pages
- 100+ custom components
- DataTables with sorting/filtering
- Real-time analytics dashboard
- Dark/light theme toggle

#### **User Site (Vite + React)**

<div align="center">

![Vite](https://img.shields.io/badge/Vite_5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript_5-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v6-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

</div>

**Key Libraries:**
- `@tanstack/react-query` ^5.56 - Server state management
- `react-router-dom` ^6.30 - Routing
- `react-hook-form` ^7.62 - Form handling
- `zod` ^3.25 - Validation
- `framer-motion` ^12.23 - Smooth animations
- `shadcn/ui` - 30+ UI components
- `embla-carousel-react` ^8.0 - Product carousels
- `react-share` ^5.2 - Social sharing
- `axios` ^1.12 - HTTP client

**Features:**
- 30+ customer-facing pages
- 80+ reusable components
- Mobile-first responsive design
- Smooth page transitions
- Guest checkout support

#### **DevOps & Tools**

<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_18+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

</div>

**Deployment:**
- Backend: Laravel Forge / Heroku
- Frontend: Vercel (both admin & user site)
- Storage: AWS S3
- Database: MySQL 8.0+
- Queue Worker: Redis + Laravel Queue

### 📈 Project Impact & Scale

<div align="center">

| Metric | Count |
|--------|-------|
| 🗄️ **Database Tables** | 55 tables |
| 📝 **Backend Code** | 3,540+ lines (services only) |
| 🧪 **Test Coverage** | 20+ feature tests, 118+ assertions |
| 📧 **Email Templates** | 12 automated templates |
| 🎨 **Components** | 180+ (admin + user combined) |
| 🔄 **API Endpoints** | 150+ RESTful endpoints |
| ⚙️ **Order Statuses** | 13 automated workflows |
| 📊 **Admin Features** | 15+ management modules |

</div>

### ⚡ Performance Metrics

<div align="center">

| Metric | Performance |
|--------|-------------|
| 🚀 **Page Load Time** | < 2 seconds (average) |
| 📱 **Mobile Performance** | Optimized & responsive |
| ⏱️ **API Response Time** | < 200ms (average) |
| 🔄 **Uptime** | 99.9% availability |
| 📦 **Bundle Size** | Optimized with code splitting |
| 🖼️ **Images** | WebP format, lazy loading |

</div>

**Performance Optimizations:**
- ✅ Code splitting per route
- ✅ Lazy loading components
- ✅ Image optimization (WebP conversion)
- ✅ Browser caching strategies
- ✅ Database query optimization
- ✅ Redis caching for frequent queries
- ✅ CDN for static assets

### 🎯 Business Features Highlights

✅ **Physical Product E-commerce**  
✅ **Digital Product Activation** (automatic)  
✅ **Down Payment System** (30% DP)  
✅ **Payment Gateway** (Midtrans - 15+ methods)  
✅ **Shipping Integration** (RajaOngkir - 3 couriers)  
✅ **Order Cancellation** (24-hour window + refunds)  
✅ **Design Proof Approval** workflow  
✅ **Review & Rating** system  
✅ **Promo Codes** (percentage & fixed)  
✅ **Email Notifications** (12 templates)  
✅ **Admin Analytics** dashboard  
✅ **Guest Checkout** support  
✅ **Invoice Generation** (PDF)  

### 📚 Documentation

The project includes comprehensive documentation:
- API Documentation (Swagger/OpenAPI)
- Feature Documentation (2000+ lines)
- Testing Guide & Checklist
- Deployment Guide
- Quick Start Guide
- Architecture Documentation

---

## 🛠️ Technical Skills

### Frontend Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend Development
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Database & Caching
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-D82C20?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### State Management & Data Fetching
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)
![Context API](https://img.shields.io/badge/Context_API-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Testing
![PHPUnit](https://img.shields.io/badge/PHPUnit-336699?style=for-the-badge&logo=php&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

### Currently Exploring
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-000000?style=for-the-badge&logo=socket.io&logoColor=white)

---

## 💡 Other Notable Projects

### 🍰 Cake E-Commerce Platform
A full-stack e-commerce solution for a bakery business with complete shopping experience

<div align="center">

[![Backend](https://img.shields.io/badge/Backend-Laravel-FF2D20?style=flat-square&logo=laravel)](https://github.com/ihza6661/cake-backend)
[![Frontend](https://img.shields.io/badge/Frontend-Vue.js-4FC08D?style=flat-square&logo=vue.js)](https://github.com/ihza6661/cake-user-site)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=flat-square&logo=mysql)](https://github.com/ihza6661/cake-backend)

</div>

**Key Features:**
- 🛒 Complete shopping cart system with session management
- 📦 Order processing and tracking
- 💳 Payment integration ready
- 👨‍💼 Admin panel for product and order management
- 📊 Sales analytics dashboard
- 🖼️ Product gallery with categories
- ⭐ Product reviews and ratings

**Tech Stack:**
- Backend: Laravel (PHP) + MySQL
- Frontend: Vue.js + Vuex
- Styling: Bootstrap + Custom CSS

🔗 **Repositories:** [Backend](https://github.com/ihza6661/cake-backend) | [Frontend](https://github.com/ihza6661/cake-user-site)

---

### 🍪 Brownies Landing Page
Modern, animated landing page for a brownies business with responsive design

[![Live Demo](https://img.shields.io/badge/Status-Live-success?style=flat-square)](https://github.com/ihza6661/Brownies)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript)](https://github.com/ihza6661/Brownies)

**Key Features:**
- 🎨 Modern, clean design with smooth animations
- 📱 Fully responsive (mobile, tablet, desktop)
- 📧 Contact form with validation
- 🖼️ Product showcase gallery
- ⚡ Fast loading with optimized assets
- 🎯 SEO optimized

**Tech Stack:**
- Vanilla JavaScript (ES6+)
- Modern CSS (Flexbox, Grid)
- HTML5 Semantic markup

🔗 **Repository:** [View Code](https://github.com/ihza6661/Brownies)

---

**[📦 See all 24 repositories →](https://github.com/ihza6661?tab=repositories)**

---

## 📊 GitHub Stats

<div align="center">

![Ihza's GitHub stats](https://github-readme-stats.vercel.app/api?username=ihza6661&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ihza6661&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ihza6661&theme=tokyonight&hide_border=true)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ihza6661&theme=tokyo-night&hide_border=true)](https://github.com/ihza6661)

</div>

---

## 🤝 Let's Connect & Collaborate!

I'm actively seeking **freelance opportunities** and **full-time positions**. Let's build something amazing together!

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ihzahmahendra6661@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://portfolio.ihza.me)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ihza_baker)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6289692070270)

</div>

### 💼 Open For:

<table align="center">
  <tr>
    <td align="center">✅ <b>Freelance Projects</b><br/>(Web Dev, API Dev, Full Stack)</td>
    <td align="center">✅ <b>Full-time Opportunities</b><br/>(Frontend, Backend, Full Stack)</td>
  </tr>
  <tr>
    <td align="center">✅ <b>Technical Consulting</b><br/>(Laravel, React, Next.js)</td>
    <td align="center">✅ <b>Open Source Collaborations</b><br/>(E-commerce, SaaS projects)</td>
  </tr>
</table>

### 📧 Contact Information

- **Email:** [ihzahmahendra6661@gmail.com](mailto:ihzahmahendra6661@gmail.com)
- **Portfolio:** [portfolio.ihza.me](https://portfolio.ihza.me)
- **Instagram:** [@ihza_baker](https://instagram.com/ihza_baker)
- **WhatsApp:** [+62 896-9207-0270](https://wa.me/6289692070270)
- **Location:** Pontianak, Indonesia 🇮🇩
- **Timezone:** UTC +07:00 (WIB)

---

<div align="center">
  
### 💡 "Code is like humor. When you have to explain it, it's bad." – Cory House

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=ihza6661.ihza6661)

<i>⭐️ Feel free to star this repository if you find it helpful!</i>

**Made with ❤️ and lots of ☕**

</div>
