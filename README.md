<div align="center">

# Hi, I'm Sylvio Lima 👋
### Full-Stack Software Engineer · Florida, USA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sylviolima-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/sylviolima)
[![Email](https://img.shields.io/badge/Email-dmsylvio@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:dmsylvio@gmail.com)
[![Location](https://img.shields.io/badge/Zephyrhills,_FL-USA-lightgrey?style=flat&logo=googlemaps&logoColor=white)](#)

</div>

---

## About Me

I'm a full-stack developer with 10+ years of experience building web products — from enterprise government systems to SaaS platforms and client-facing websites. I specialize in **TypeScript**, **React/Next.js**, **Node.js**, and **PostgreSQL**, and I take pride in shipping things that actually work in production.

Currently completing the **Springboard Software Development Career Program** (Amazon Career Choice sponsored) and building [Orgaflow](https://orgaflow.dev) — a multi-tenant SaaS for small business workflows — from zero to public beta.

I care about clean architecture, real documentation, and products that solve real problems.

---

## 🚀 Live Projects

### [Orgaflow](https://orgaflow.dev) — Multi-tenant SaaS Platform
> *Customers · Estimates · Invoices · Payments · Automations · Kanban*

A full-featured business workflow platform built for small teams. Serving **200+ businesses** in public beta with **98.9% uptime**.

- **Multi-tenant architecture** — each user can belong to multiple organizations; all actions are org-scoped via `x-organization-id` header or cookie
- **Full RBAC/IAM** — owner bypass, role-based `resource:action` permissions with automatic dependency expansion
- **Type-safe API** with tRPC v11 + Zod + SuperJSON, integrated with TanStack React Query
- **Public client portal** — shareable estimate/invoice links with approve/reject flow, PDF download, and attachment previews
- **File storage** with Vercel Blob + DB-backed file catalog with per-document visibility controls
- **Automation engine** — connect domain events (estimate approved, invoice paid) to automatic task creation
- **Stripe subscriptions** with plan-based feature gating server-side
- **PDF generation** server-side with `@react-pdf/renderer` for estimates and invoices
- Stack: `Next.js 16` · `React 19` · `tRPC v11` · `Drizzle ORM` · `PostgreSQL` · `Auth.js` · `Stripe` · `Vercel Blob` · `Resend` · `Zod` · `Tailwind CSS`
- 📌 *Private repository — production app live at [orgaflow.dev](https://orgaflow.dev)*

---

### [Every Party Decor](https://everypartydecor.com) — Full-Stack Rental Management Platform
> *Party rental & decor operations — Everett, Massachusetts*

Full-stack platform replacing a legacy PHP/MySQL/Yii2 system. Decoupled architecture with a Fastify REST API and a React SPA, covering the complete rental business lifecycle.

- **Fastify 5 REST API** with OpenAPI docs (Scalar UI) at [api.everypartydecor.com/docs](https://api.everypartydecor.com/docs)
- **React 19 + Vite** SPA with protected back-office (`/app`) and public-facing estimate/invoice pages
- **Period-based stock control** — prevents overbooking across overlapping rental date ranges; only confirmed invoices reserve inventory
- **Full rental workflow** — customers, rental items, categories, estimates (quotes), invoices, payments, expenses, and contracts
- **JWT authentication** + bcryptjs password hashing, with guest-only and protected route separation
- **PDF generation** (pdf-lib) + email delivery (Resend) for estimates and invoices
- **TanStack Query** + React Hook Form + Zod for type-safe data fetching and form validation
- Stack: `Fastify 5` · `React 19` · `Vite` · `TypeScript` · `PostgreSQL` · `Drizzle ORM` · `JWT` · `Zod` · `Tailwind CSS`
- 📌 *Private repository — live at [everypartydecor.com](https://everypartydecor.com)*

---

### [Brasília Estágios](https://brasiliaestagios.com.br) — Internship Platform
> *Connecting students, companies & institutions — Brasília, Brazil · 8,000+ active listings*

Full platform for managing the internship lifecycle in Brazil's Federal District. Originally built in PHP/Yii2; currently being rebuilt from scratch (v2) with a modern type-safe stack designed to also support a mobile client.

- **Four-role system** — students, companies, institutions, and admins, each with scoped access enforced client and server-side
- **Auth flows** — sign up with role selection, sign in, forgot-password (6-digit code), and password reset
- **Type-safe API** with tRPC v11 + TanStack Query; same API contract will be consumed by the mobile app
- **Full domain schema** in Drizzle ORM — internship opportunities, agreement requests, commitment terms, representatives, supervisors, and more
- **Centralized Zod validation** shared between server procedures and UI forms, with errors surfaced via tRPC's `errorFormatter`
- **Mobile app** in React Native (Expo) planned to consume the same tRPC API
- Stack (v1): `PHP` · `Yii2` · `PostgreSQL` · `JavaScript`
- Stack (v2): `Next.js 16` · `React 19` · `tRPC v11` · `Auth.js` · `PostgreSQL` · `Drizzle ORM` · `Zod` · `Tailwind CSS` · `shadcn/ui` · `React Native` · `Expo`
- 📌 *Private repository — live at [brasiliaestagios.com.br](https://brasiliaestagios.com.br)*

---

## 🛠️ Tech Stack

**Languages**
`TypeScript` · `JavaScript` · `PHP` · `SQL`

**Frontend & Mobile**
`React` · `Next.js` · `React Native` · `Expo` · `Tailwind CSS` · `Zod`

**Backend**
`Node.js` · `Express.js` · `tRPC` · `Yii2`

**Databases**
`PostgreSQL` · `MySQL` · `Drizzle ORM`

**Infrastructure & Auth**
`DNS` · `SSL` · `CDN` · `Auth.js` · `LDAP/SSO` · `Stripe`

**Tools**
`Git` · `Linux` · `Docker` · `Biome` · `pnpm`

---

## 📋 Professional Experience Highlights

- **Full-Stack Developer @ INMET** (Brazilian National Weather Service) — legacy system modernization, React/Next.js adoption, PostgreSQL optimization, LDAP SSO implementation
- **WordPress Developer @ Switch Design Team** (Peabody, MA) — end-to-end client site delivery, CDN/performance optimization, staging-to-production workflows
- **Full-Stack Developer @ Boa Imagem** — PHP SaaS platforms, third-party API integrations, full-lifecycle client project ownership

---

## 📚 Currently

- 🎓 Completing **Springboard Software Development Career Program** (Expected May 2026)
- 🏗️ Building new features for [Orgaflow](https://orgaflow.dev) — automations, reports, public API
- ☁️ AWS Certified: EC2 for Windows Instances (Sept 2025)

---

<div align="center">

*"Ship things. Document them. Make them work."*

</div>
