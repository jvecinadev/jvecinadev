<div align="center">

# John Francis Vecina

**Full Stack Developer, MERN & TypeScript**

<p>
  <a href="https://www.linkedin.com/in/john-francis-vecina-a76aa63b9/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://jvecina-dev.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=google-chrome&logoColor=white"/>
  </a>
  <a href="mailto:johnvecina640@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>

</div>

---

## About

IT student and full stack developer with hands-on experience building production-style web applications end to end: UI, REST APIs, database design, and deployment. Primary stack is MERN and TypeScript, with recent work spanning Prisma, MySQL, and multi-tenant application architecture.

## Projects

### Plinth
Multi-tenant SaaS platform for managing clients, projects, and tasks across team workspaces, with role-based access control and a metrics dashboard.

- Workspace-based tenancy with roles (owner, admin, member, viewer), member invites, and workspace switching
- Zod validation on every API route, JWT auth via HTTP-only cookies
- Jest + Supertest integration suite covering tenant isolation and soft-delete behavior
- Dashboard backed by MongoDB aggregation pipelines, cached in Redis
- Dockerized frontend and backend with a GitHub Actions pipeline running build and test on every push

**Stack:** React 19, TypeScript, Node.js, Express 5, MongoDB, Redis, Zod, Jest, Docker

[View Repository](https://github.com/jvecinadev/plinth)

### Bantay PH
Full-stack community issue-reporting platform for local government use. Residents submit reports, validators verify them, and staff resolve them through an enforced status workflow with a complete audit trail.

- Database-driven RBAC, with role-to-permission mapping resolved per request rather than hardcoded or baked into the JWT
- Enforced report lifecycle state machine with transactional, race-condition-safe status updates
- Prisma schema modeled with deliberate constraints: decimal-precision coordinates, unique verification per validator, and per-relation cascade/restrict delete rules
- React frontend with TanStack Query for server state, Zustand for auth state, and a Leaflet-based location picker

**Stack:** React 19, TypeScript, Express 5, Prisma, MySQL, TanStack Query, Zustand, Tailwind CSS

[View Repository](https://github.com/jvecinadev/bantay-ph)

## Tech Stack

**Frontend**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zustand-433E38?style=flat-square"/>
</p>

**Backend & Database**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
</p>

**Testing & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

**Tools & Platforms**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
</p>

---

<div align="center">

[LinkedIn](https://www.linkedin.com/in/john-francis-vecina-a76aa63b9/) · [Portfolio](https://jvecina-dev.vercel.app/) · [Email](mailto:johnvecina640@gmail.com)

</div>
