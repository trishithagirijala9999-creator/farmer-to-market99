# 🌾 AgriDirect – West Godavari

### Direct Farm-to-Market Agricultural Marketplace for West Godavari, Andhra Pradesh

AgriDirect is a **Smart India Hackathon prototype** that connects farmers directly with buyers through a digital agricultural marketplace.

The platform is designed to help farmers list their agricultural produce, reach buyers directly, improve price transparency, and reduce unnecessary dependence on intermediaries.

The application focuses on the **West Godavari region of Andhra Pradesh** and provides a simple, mobile-friendly experience with **English and Telugu** language support.

---

## 🎯 Problem Statement

Farmers often face difficulties in:

* Reaching buyers directly
* Finding fair market prices
* Getting transparent information about buyers
* Selling produce without depending heavily on intermediaries
* Managing orders and customers digitally

Buyers also face challenges in finding fresh agricultural produce directly from local farmers.

### 💡 Our Solution

AgriDirect provides a digital platform where:

**Farmers → List Produce → Buyers Discover → Negotiate/Buy → Orders Tracked**

The platform creates a direct connection between agricultural producers and buyers.

---

## 🚀 Key Features

### 🌾 Farmer Features

* Farmer registration and login
* Farmer profile
* Farmer dashboard
* Add agricultural produce
* Edit own listings
* Delete own listings
* View available listings
* View incoming buyer orders
* Accept or reject orders
* Update order status
* View earnings
* Upload produce photographs
* Simple mobile-friendly farmer interface

### 🛒 Buyer Features

* Buyer registration and login
* Buyer dashboard
* Browse agricultural marketplace
* Search produce
* Filter by category
* Filter by mandal
* Filter by price
* View product details
* View farmer information
* Wishlist products
* Buy produce
* Make offers
* View own orders
* Track order status

### 👨‍💼 Admin Features

* Admin login
* Admin dashboard
* View farmers
* View buyers
* View products
* View orders
* Monitor marketplace activity

---

## 🌱 Agricultural Products

The marketplace supports different agricultural categories, including:

### 🌾 Crops

* Paddy
* Sugarcane

### 🍌 Fruits

* Banana
* Coconut

### 🥬 Vegetables

* Tomato
* Brinjal / Vankaya
* Green Chilli
* Okra / Bendakaya
* Spinach and leafy vegetables
* Other seasonal vegetables

The marketplace uses **realistic, category-specific agricultural photographs** so that products are visually represented according to the actual produce being sold.

---

## 🤖 AI Prototype Features

AgriDirect includes prototype AI functionality designed for future expansion.

Potential AI-assisted features include:

* 🌾 AI-based price recommendations
* 📈 Agricultural demand forecasting
* 🤝 Smart buyer-product matching

These AI features are currently considered **prototype/demo functionality** and should not be treated as live market predictions unless connected to validated real-world datasets and production ML models.

---

## 🌐 Language Support

The platform supports:

* 🇬🇧 English
* 🇮🇳 Telugu (తెలుగు)

Telugu support is particularly important for making the farmer-facing interface easier to use for local agricultural communities in Andhra Pradesh.

---

## 📍 Regional Focus

### West Godavari, Andhra Pradesh

AgriDirect is designed around agricultural trade in the West Godavari region.

The marketplace can contain listings based on:

* Villages
* Mandals
* Farmer locations
* Agricultural produce available in the region

---

## 👥 User Roles

The application contains three primary user roles:

### 👨‍🌾 Farmer

Farmers can:

* Manage their profile
* Add and manage produce
* Upload produce images
* Receive buyer orders
* Accept/reject orders
* Update order status
* Track earnings

### 🛒 Buyer

Buyers can:

* Browse agricultural products
* Search and filter produce
* View farmer information
* Add products to wishlist
* Make offers
* Purchase produce
* Track orders

### 👨‍💼 Admin

Administrators can:

* View farmers
* View buyers
* View products
* View orders
* Monitor the platform

---

## 🛠️ Technology Stack

### Frontend

* React
* TypeScript
* Tailwind CSS
* Vite
* Responsive Web Design

### Backend / Services

* Supabase
* Supabase Authentication
* Supabase Database
* Role-based access structure

### AI

* Prototype AI services
* Future ML-based price prediction
* Future demand forecasting

### Development & Deployment

* GitHub
* Vercel
* Google AI Studio / Emergent AI for development assistance

---

## 🏗️ Application Structure

```text
AgriDirect
│
├── Public Pages
│   ├── Home
│   ├── Marketplace
│   ├── How It Works
│   ├── About
│   ├── Login
│   └── Register
│
├── Farmer
│   ├── Dashboard
│   ├── Profile
│   ├── Add Produce
│   ├── Manage Listings
│   ├── Orders
│   └── Earnings
│
├── Buyer
│   ├── Dashboard
│   ├── Marketplace
│   ├── Product Details
│   ├── Wishlist
│   └── Orders
│
└── Admin
    ├── Dashboard
    ├── Farmers
    ├── Buyers
    ├── Products
    └── Orders
```

---

## 🔐 Authentication & Security

The application uses Supabase authentication and follows a role-based access structure.

The system is designed to ensure that:

* Users can access appropriate dashboards based on their role
* Farmers can manage their own listings
* Buyers can access their own orders
* Admin functionality is restricted to administrators
* Protected pages require authentication
* Supabase service-role keys are never exposed in frontend code

---

## 📱 Responsive Design

AgriDirect follows a **mobile-first design approach**.

The farmer interface is intentionally kept simple because farmers may primarily access the platform through smartphones.

The application is designed to work across:

* 📱 Mobile
* 💻 Desktop
* 🖥️ Larger screens

---

## 🔄 Order Workflow

The planned order workflow is:

```text
Order Placed
      ↓
Farmer Accepts
      ↓
Preparing
      ↓
Ready for Pickup
      ↓
Out for Delivery
      ↓
Delivered
```

This provides buyers with visibility into the progress of their orders.

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/trishithagirijala24-source/agri-direct-west-godavari.git
```

### 2. Navigate to the Project

```bash
cd agri-direct-west-godavari
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file based on `.env.example`.

Example:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Do **not** add private service-role keys to frontend environment variables.

### 5. Start Development Server

```bash
npm run dev
```

The application will then be available through the local development URL shown by Vite.

---

## 🚀 Deployment

The project can be deployed using Vercel.

Production deployment:

**AgriDirect – West Godavari**

The GitHub `main` branch can be connected to Vercel so that future commits can trigger new deployments.

---

## 🧪 Testing

Before a production release, test:

* Authentication
* Farmer registration/login
* Buyer registration/login
* Admin access
* Protected routes
* Add/edit/delete produce
* Marketplace search
* Marketplace filters
* Product details
* Wishlist
* Order creation
* Order status updates
* Farmer image uploads
* Telugu language interface
* Mobile responsiveness
* Missing/invalid product images
* Supabase integration

---

## 🔮 Future Enhancements

Future versions of AgriDirect may include:

* 💳 Razorpay/UPI payment integration
* 🗺️ Google Maps delivery tracking
* 🔔 Real-time order notifications
* 📊 Advanced marketplace analytics
* 🤖 Production AI price prediction
* 📈 Real-time demand forecasting
* 🚚 Delivery partner module
* 📸 Advanced produce image verification
* ⭐ Buyer and farmer ratings
* 💬 Buyer-farmer communication
* 📱 Progressive Web App
* 🌾 Integration with verified agricultural market data

---

## 🏆 Smart India Hackathon

**Project Name:** AgriDirect – West Godavari

**Concept:** Farmer-to-Market Digital Marketplace App for West Godavari Produce

**Theme:** Agriculture / Digital Marketplace / Rural Technology

**Region:** West Godavari, Andhra Pradesh

**Developed for:** Smart India Hackathon 2026

---

## 👥 Team Structure

Our six-member team divides the project into specialized responsibilities:

| Member      | Role                                     | Responsibility                                                  |
| ----------- | ---------------------------------------- | --------------------------------------------------------------- |
| 👑 Member 1 | **Team Lead & System Architect**         | Project planning, architecture, coordination and integration    |
| 🎨 Member 2 | **Frontend & UI/UX Developer**           | React, TypeScript, Tailwind CSS and responsive interface        |
| ⚙️ Member 3 | **Backend & Database Developer**         | Supabase, authentication, database and access control           |
| 🌾 Member 4 | **Farmer & Marketplace Developer**       | Farmer module, produce listings, marketplace and product images |
| 🛒 Member 5 | **Buyer, Orders & Admin Developer**      | Buyer module, orders, tracking and admin dashboard              |
| 🤖 Member 6 | **AI/ML, Testing & Deployment Engineer** | AI prototypes, testing, debugging, GitHub and Vercel deployment |

---

## ⚠️ Prototype Notice

AgriDirect is a **Smart India Hackathon prototype**.

Some farmer profiles, marketplace listings, prices, AI predictions and other information may use demonstration data.

The prototype should not be interpreted as providing government-verified agricultural market prices, financial services or real payment processing unless the corresponding production services are integrated and verified.

---

## 🌾 Vision

Our vision is to create a simple digital bridge between **West Godavari farmers and buyers**, helping agricultural producers reach markets directly while making the buying process more transparent and accessible.

> **AgriDirect – Connecting Farmers Directly to Markets. 🌾**

---

## 📄 License

This project is developed as a prototype for **Smart India Hackathon 2026**.
