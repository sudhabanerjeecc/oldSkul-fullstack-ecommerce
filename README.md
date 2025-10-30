# 👕 Clothing E-Commerce Website  
Built with **React + TypeScript + Supabase + Tailwind CSS**

A modern, scalable, and production-ready e-commerce platform for clothing brands — built with React, TypeScript, and Supabase as the backend (Auth, Database, Storage).

---

## 🚀 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend** | React 18 (Vite) + TypeScript |
| **Backend / Database** | Supabase (PostgreSQL + Auth + Storage) |
| **State Management** | Redux Toolkit + React Context |
| **Styling** | Tailwind CSS or Bootstrap |
| **Routing** | React Router v6 |
| **Forms** | React Hook Form |
| **Utilities** | ESLint + Prettier for code quality |
| **Testing** | Vitest / Jest + React Testing Library |

---

## 🏗️ Folder Structure
```bash
oldSkul-ecommerce/
├── .env
├── package.json
├── README.md
├── tsconfig.json
├── vite.config.ts
├── public/
│   ├── favicon.ico
│   └── (static assets: logo, images, icons)
└── src/
    ├── api/
    │   ├── auth.api.ts
    │   ├── cart.api.ts
    │   ├── orders.api.ts
    │   ├── products.api.ts
    │   └── supabaseClient.ts
    ├── app/
    │   ├── App.tsx
    │   └── routes/
    │       ├── cart.tsx
    │       ├── category.tsx
    │       ├── checkout/
    │       │   ├── index.tsx
    │       │   ├── payment.tsx
    │       │   └── shipping.tsx
    │       ├── forgotten-password.tsx
    │       ├── index.tsx (Home page)
    │       ├── login.tsx
    │       ├── product.tsx
    │       └── register.tsx
    ├── components/
    │   ├── cart/
    │   ├── category/
    │   ├── checkout/
    │   ├── common/ (Buttons, Inputs, Modals, etc.)
    │   ├── layout/ (Header, Footer, Navbar, Layout)
    │   └── product/
    ├── context/
    │   ├── AuthContext.tsx
    │   ├── CartContext.tsx
    │   └── ThemeContext.tsx
    ├── hooks/
    │   ├── useAuth.ts
    │   ├── useCart.ts
    │   ├── useFetch.ts
    │   └── useProductFilter.ts
    ├── redux/
    │   ├── slices/
    │   │   ├── authSlice.ts
    │   │   ├── cartSlice.ts
    │   │   ├── categorySlice.ts
    │   │   └── productSlice.ts
    │   └── store.ts
    ├── styles/
    │   ├── globals.css
    │   ├── tailwind.css
    │   └── variables.css
    ├── types/
    │   ├── auth.types.ts
    │   ├── cart.types.ts
    │   ├── category.types.ts
    │   ├── order.types.ts
    │   └── product.types.ts
    ├── utils/
    │   ├── constants.ts
    │   ├── formatPrice.ts
    │   ├── handleError.ts
    │   └── validateEmail.ts
    ├── main.tsx
    └── vite-env.d.ts

```

---

## ⚙️ Environment Variables

Create a `.env` file in the project root:

```bash
VITE_SUPABASE_URL=https://yourproject.supabase.co
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

🪄 Setup & Installation
1️⃣ Clone the repository
git clone https://github.com/sudhabanerjeecc/oldSkul-fullstack-ecommerce.git
cd clothing-ecommerce

2️⃣ Install dependencies
npm install

3️⃣ Configure environment variables

Add your Supabase credentials inside .env.

4️⃣ Run the development server
npm run dev


The app should now be running at http://localhost:5173