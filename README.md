<div align="center">

<img src="https://placehold.co/120x120/1a1a2e/ffffff?text=M&font=montserrat" alt="Matgar Logo" width="100" height="100" style="border-radius: 20px;" />

# متجر · Matgar

### The E-Commerce Builder for Arab Merchants

**Launch your online store in minutes — your brand, your domain, your rules.**

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![.NET](https://img.shields.io/badge/.NET-9-512BD4?style=flat-square&logo=dotnet)](https://dotnet.microsoft.com/)
[![Flutter](https://img.shields.io/badge/Flutter-3.41-02569B?style=flat-square&logo=flutter)](https://flutter.dev/)
[![Paymob](https://img.shields.io/badge/Payments-Paymob-00C853?style=flat-square)](https://paymob.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

<br/>

> *Every merchant deserves a store that looks like a million dollars —*
> *without spending like it.*

<br/>

[**Live Demo**](https://matgar.tech) · [**Docs**](#) · [**Report a Bug**](#) · [**Request a Feature**](#)

</div>

---

## ✦ What is Matgar?

**Matgar** || **متجر** is a full-stack **e-commerce builder** — not a marketplace, not a template pack. When a merchant signs up, they get:

- A **fully isolated store website** deployed on their own subdomain → `your-brand.matgar.tech`
- A **web dashboard** to manage everything from orders to themes
- A **mobile app** as a pocket-sized dashboard for managing the business on the go

> ⚠️ The mobile app is **not** a storefront for end customers. It's a merchant management tool — the same power as the web dashboard, in your pocket.

---

## ✦ Feature Highlights

### 🏪 Storefront (Customer-Facing)
The generated store each merchant gets is a polished, performant Next.js site with:

| Feature | Description |
|---|---|
| 🔍 **Smart Search** | Intelligent product search with filters and instant results |
| 🤝 **Recommendation Engine** | Personalized product suggestions per session |
| 💳 **Flexible Checkout** | Pay with Visa via Paymob or Cash on Delivery |
| 👤 **Guest Checkout** | Buy without creating an account — zero friction |
| 🌐 **Custom Subdomain** | Every store lives at `storename.matgar.tech` |

---

### 🖥️ Merchant Dashboard (Web + Mobile)

The control center for merchants. Available on both web and Flutter mobile app.

<details>
<summary><strong>📊 Analytics</strong></summary>

> Sales trends, revenue overview, top-performing products, and order statistics — all in one view.

</details>

<details>
<summary><strong>🎨 Theme Editor</strong></summary>

> Drag-and-drop visual editor to customize the storefront's look and feel. Change layouts, colors, fonts, and sections — no code required.

</details>

<details>
<summary><strong>🤖 AI Page Builder</strong></summary>

> Describe your store in plain Arabic or English, and the AI generates a full **Homepage layout** with sections, copy, and structure — ready to publish.

</details>

<details>
<summary><strong>📦 Products & Categories</strong></summary>

> Full product management: add items, organize by category, attach images, set prices, manage inventory.

</details>

<details>
<summary><strong>🎛️ Options</strong></summary>

> Define reusable product options like sizes, colors, materials — then attach them to any product.

</details>

<details>
<summary><strong>📋 Orders</strong></summary>

> Real-time order tracking, status updates, and order history. Get notified the moment a sale comes in.

</details>

<details>
<summary><strong>💳 Payment Settings</strong></summary>

> Connect your Paymob account to start accepting card payments instantly. Configure payment methods per store.

</details>

<details>
<summary><strong>🧾 Billing</strong></summary>

> Manage your Matgar subscription, view invoices, and upgrade or downgrade your plan.

</details>

---

## ✦ Architecture Overview

```
matgar.tech (Platform)
│
├── web/                        # Next.js — Merchant Dashboard + Storefront Generator
│   ├── dashboard/              # Merchant control panel
│   └── [store].matgar.tech/    # Dynamically served storefronts per subdomain
│
├── api/                        # .NET Web API — Core backend
│   ├── Auth & Tenancy
│   ├── Products, Orders, Categories
│   ├── AI Page Builder (LLM integration)
│   └── Paymob Payment Gateway
│
└── mobile/                     # Flutter — Merchant Dashboard App
    ├── Analytics
    ├── Orders Management
    ├── Products & Categories
    └── Theme Preview
```

---

## ✦ Tech Stack

| Layer | Technology |
|---|---|
| **Storefront & Dashboard** | Next.js 15 |
| **Backend API** | ASP.NET Core (.NET 9) |
| **Mobile App** | Flutter 3.41.6 |
| **Database** | PostgreSQL |
| **Payments** | Paymob |
| **AI Builder** | LLM API (OpenAI / Claude) |
| **Subdomains** | Wildcard DNS + Dynamic Routing |


---

## ✦ Screenshots

> 📸 *Screenshots and demo GIFs coming soon.*

| Dashboard | Theme Editor | AI Builder | Mobile App |
|:---------:|:------------:|:----------:|:----------:|
| ![placeholder](https://placehold.co/220x140/1a1a2e/aaaacc?text=Dashboard&font=montserrat) | ![placeholder](https://placehold.co/220x140/1a1a2e/aaaacc?text=Theme+Editor&font=montserrat) | ![placeholder](https://placehold.co/220x140/1a1a2e/aaaacc?text=AI+Builder&font=montserrat) | ![placeholder](https://placehold.co/220x140/1a1a2e/aaaacc?text=Mobile+App&font=montserrat) |

---

## ✦ Roadmap

- [x] Multi-tenant subdomain architecture
- [x] Paymob payment integration
- [x] AI-powered page builder
- [x] Drag & drop theme editor
- [x] Mobile dashboard (Flutter)
- [ ] Custom domain support (`www.yourstore.com`)
- [x] Multi-language storefront (AR/EN)
- [ ] Storefront SEO tools
- [ ] Abandoned cart recovery
- [ ] Mobile push notifications

---


## ✦ Team

> This project was built as a graduation project by:
 
| Name | Role |
|---|---|
| **Yousef Dewidar** | Mobile / Team Lead |
| **Fares Mahmoud** | Backend |
| **Abdelfatah Elsabagh** | Cyber Security |
| **Rana Fathi** | AI |
| **Ahmed Abusetta** | Frontend |
| **Zakaria Reda** | Frontend |
| **Ahmed Ebeed** | Frontend |
 
---

## ✦ License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

Built with ❤️ in Egypt · Graduation Project · [matgar.tech](https://matgar.tech)

</div>
