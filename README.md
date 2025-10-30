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

clothing-ecommerce/
│
├── public/ # Static assets (logo, images, icons)
│
├── src/
│ ├── api/ # API layer for Supabase requests
│ │ ├── supabaseClient.ts
│ │ ├── auth.api.ts
│ │ ├── products.api.ts
│ │ ├── cart.api.ts
│ │ └── orders.api.ts
│ │
│ ├── app/ # Main app routing and pages
│ │ ├── App.tsx
│ │ └── routes/
│ │ ├── index.tsx # Home page
│ │ ├── cart.tsx
│ │ ├── category.tsx
│ │ ├── checkout/
│ │ │ ├── index.tsx
│ │ │ ├── payment.tsx
│ │ │ └── shipping.tsx
│ │ ├── product.tsx
│ │ ├── login.tsx
│ │ ├── register.tsx
│ │ └── forgotten-password.tsx
│ │
│ ├── components/ # Reusable and modular components
│ │ ├── common/ # Buttons, Inputs, Modals, etc.
│ │ ├── layout/ # Header, Footer, Navbar, Layout
│ │ ├── cart/
│ │ ├── checkout/
│ │ ├── product/
│ │ └── category/
│ │
│ ├── context/ # Global context providers
│ │ ├── AuthContext.tsx
│ │ ├── CartContext.tsx
│ │ └── ThemeContext.tsx
│ │
│ ├── hooks/ # Custom reusable hooks
│ │ ├── useAuth.ts
│ │ ├── useCart.ts
│ │ ├── useFetch.ts
│ │ └── useProductFilter.ts
│ │
│ ├── redux/ # Redux Toolkit setup
│ │ ├── store.ts
│ │ ├── slices/
│ │ │ ├── authSlice.ts
│ │ │ ├── cartSlice.ts
│ │ │ ├── productSlice.ts
│ │ │ └── categorySlice.ts
│ │
│ ├── types/ # TypeScript types & interfaces
│ │ ├── auth.types.ts
│ │ ├── cart.types.ts
│ │ ├── product.types.ts
│ │ ├── category.types.ts
│ │ └── order.types.ts
│ │
│ ├── utils/ # Helper functions
│ │ ├── formatPrice.ts
│ │ ├── validateEmail.ts
│ │ ├── handleError.ts
│ │ └── constants.ts
│ │
│ ├── styles/ # Global & Tailwind setup
│ │ ├── globals.css
│ │ ├── variables.css
│ │ └── tailwind.css
│ │
│ ├── main.tsx # Vite entry point
│ └── vite-env.d.ts
│
├── .env # Environment variables (Supabase keys)
├── tsconfig.json
├── vite.config.ts
├── package.json
└── README.md


---

## ⚙️ Environment Variables

Create a `.env` file in the project root:

```bash
VITE_SUPABASE_URL=https://yourproject.supabase.co
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

🪄 Setup & Installation
1️⃣ Clone the repository
git clone https://github.com/your-username/clothing-ecommerce.git
cd clothing-ecommerce

2️⃣ Install dependencies
npm install

3️⃣ Configure environment variables

Add your Supabase credentials inside .env.

4️⃣ Run the development server
npm run dev


The app should now be running at http://localhost:5173