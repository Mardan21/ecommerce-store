# E-commerce Store (Frontend)

This is the customer-facing frontend of a full-stack e-commerce platform built with **Next.js**. Users can browse products, add them to a shopping cart, and complete purchases through **Stripe**. The app communicates with a shared backend/database used by the `ecommerce-admin` dashboard.

## 🚀 Features

- Browse products with responsive, fast-loading pages (Next.js 14)
- Add/remove items from cart with persistent state using Zustand
- Checkout with secure payment integration via Stripe API
- Clean UI built with Tailwind CSS (optional if implemented)
- Connected to shared backend database via Prisma and PlanetScale

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js (React, TypeScript)
- **State Management**: Zustand
- **ORM**: Prisma
- **Database**: PlanetScale (MySQL)
- **Payments**: Stripe API
- **Other**: Supabase (optional for auth or storage, if used)

## 🧩 How It Works with [`ecommerce-admin`](https://github.com/Mardan21/ecommerce-admin) — Admin panel for managing products and tracking orders

- Both `ecommerce-store` and `ecommerce-admin` share the same PlanetScale database.
- Products added via the admin dashboard instantly appear in the store.
- When a user checks out via Stripe in this app, order and payment data are recorded in the database and can be viewed in the admin dashboard.

## 📽️ Demonstration

This app was not deployed to production.  
A demo is available on YouTube:  
🎥 [Watch the demo](https://www.youtube.com/watch?v=lq6q3VwNKbE&ab_channel=MardanMahmut)

## 📦 Skills Demonstrated

- Full-stack architecture with Next.js and Prisma
- State management using Zustand
- Third-party API integration (Stripe)
- Dynamic rendering (SSR/SSG)
- Modular component design
