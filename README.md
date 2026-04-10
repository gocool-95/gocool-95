# Hi, I'm Gokul Raj

**Product Manager & Full-Stack Engineer** based in Bengaluru, India.

I bridge the gap between product thinking and hands-on engineering — from gathering client requirements and defining roadmaps, to designing backend architectures and shipping full-stack applications.

---

## What I'm working on

- **Migrating a production B2B SaaS app** from AngularJS → Next.js (solo, with Claude Code)
- **RMG Beta** — dual-domain company management system for a granite manufacturing & services business
- **RDL** — production order management platform for dental laboratories

---

## Projects

### RDL — Dental Lab Order Management Platform
A production-grade platform replacing paper-based workflows in dental laboratories.

**Stack:** Node.js · Express · MongoDB · React · Expo (React Native) · Cloudinary · Railway

**Key highlights:**
- Order lifecycle tracking — intake to delivery (pending → in-progress → delivered)
- Role-based access control (admin and employee roles)
- OTP + PIN login with JWT and refresh token rotation
- Secure file attachments (X-rays, STL files) via signed Cloudinary URLs — raw URLs never exposed
- Brute-force lockout, CORS allow-listing, regex injection protection
- Printable Work Orders, payment tracking, patient and doctor management
- Activity log across the system | React web dashboard + Expo mobile app

---

### RMG Beta — Dual-Domain Company Management System
A comprehensive platform managing two business domains: granite machine manufacturing and granite polishing services.

**Stack:** Node.js · Express · TypeScript · MongoDB · Redis · React 18 · Expo (React Native) · Vite · Zustand · Material-UI

**Key highlights:**
- Dual-domain architecture — granite machine manufacturing and polishing services in one system
- Real-time inventory tracking, purchase requisition workflows, product catalog with online ordering
- React Native (Expo) monorepo — separate customer and company apps sharing components, API client, and types
- JWT with refresh token rotation, optional 2FA, RBAC (Admin, Employee, Customer)
- Rate limiting, bcrypt, Helmet.js, CORS, XSS/injection protection, full audit log

---

### Keego — Bali Trip Planner
A personal full-stack trip itinerary app built for an actual Bali trip.

**Stack:** Ionic 8 · React 19 · TypeScript · Node.js · Express · MongoDB · Capacitor (Android)

**Key highlights:**
- Offline-first sync via Dexie (IndexedDB) with delta updates using timestamp-based queries
- Day-by-day itinerary management, ticket image uploads, GPS coordinates, booking references
- Multi-currency payment tracking (IDR/USD), transport modes, and activity categorization
- Android app via Capacitor | Built with Claude Code

---

## 🛠 Tech Stack

**Backend:** Node.js · Express.js · MongoDB · REST APIs · JWT  
**Frontend:** React.js · Next.js · Expo (React Native)  
**Legacy:** AngularJS · Ionic 3  
**Tools:** Swagger · Git · Jira · BitBucket · Cloudinary · Railway  
**AI-assisted dev:** Claude Code  

---

## About Me

- 7+ years at Bizmobile IT Solutions — Software Developer → Deployment Lead → Product Manager
- Designed and led a **6-microservice backend + API gateway** for a POS platform (Node.js, consulting engagement)
- End-to-end client deployments including **Atmosphere Hotels & Resorts, Maldives**
- CS graduate, Global Academy of Technology (2018)

---

gokulraj.cs95@gmail.com · [LinkedIn](https://www.linkedin.com/in/gokul-raj-92415653/)
