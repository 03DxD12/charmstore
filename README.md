# ✨ Chérie Charms | Boutique Philippine Jewelry & Seller System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

> *"Little charms, big stories."* — An all-in-one boutique charm jewelry storefront, interactive custom bracelet builder, Philippine payment checkout, real-time customer order tracking, and seller management system.

---

## 📖 About The Project

**Chérie Charms** is a comprehensive, standalone e-commerce web application crafted specifically for Philippine handmade and hypoallergenic charm jewelry. Built with modern Vanilla web technologies, it delivers a high-end luxury boutique aesthetic (soft blush pink, warm cream, and muted metallic gold) coupled with a rich, responsive customer and seller experience.

---

## 🌟 Key Features

### 🛍️ 1. Boutique Storefront & Catalog
- **Category Filter Pills**: Effortlessly filter charms across categories (e.g., Celestial, Florals, Pearls, Keepsakes, Miniatures).
- **Instant Search & Sorting**: Real-time fuzzy filtering by name, tag, and price ranges (Low to High, High to Low, Most Popular).
- **Product Details & Quick Add**: Rich product cards with high-resolution imagery, pricing in Philippine Peso (`₱`), material specifications, and quick add-to-cart actions.

### ⛓️ 2. Interactive Custom Bracelet Builder
- **Visual Circular Bracelet Visualizer**: Select your preferred base chain (Gold Link, Figaro, Rose Gold, Silver Cable) and watch charms arrange in real-time along the bracelet curve.
- **Dynamic Live Pricing**: Instant breakdown of base chain cost + selected charm accessories (up to 5 charm slots).
- **Direct Cart Integration**: Pack the custom-configured bracelet directly into the shopping cart as a single bundled item with customized specifications.

### 💳 3. Philippine Checkout & Payment Flow
- **Tailored Delivery Rates**: Auto-calculated shipping fee matrix for **Metro Manila**, **Luzon**, **Visayas**, and **Mindanao**.
- **Local Payment Gateways**: Detailed instructions and payment flow for:
  - **GCash** (QR & mobile account details)
  - **Maya** (PayMaya QR & instant transfer)
  - **Cash on Delivery (COD)**
  - **Bank Transfer** (BDO / BPI)
- **Promo Code Engine**: Built-in support for discount vouchers and price deductions.

### 🚚 4. Real-Time Customer Order Tracking
- **Order Lookup**: Customers enter their order reference (e.g., `CHR-2026-0001`) to inspect their current parcel status.
- **Visual Progress Stepper**: 5-stage animated tracking pipeline (*Order Placed* ➔ *Payment Verified* ➔ *Crafting & Packing* ➔ *Handed to Courier* ➔ *Delivered*).
- **Courier Details**: Live status with logistics partner details (J&T Express, Ninja Van, Lalamove), tracking numbers, and expected delivery windows.

### 💼 5. Seller Administration Dashboard
- **Executive Analytics**: Key performance indicators including Total Sales, Pending Orders, Completed Deliveries, and Low-Stock warnings.
- **Order Management**: Change order statuses in one click, verify payment proofs, and assign courier tracking IDs.
- **Product & Inventory Control**: Add new charm designs, adjust stock counts, toggle availability, and edit pricing.
- **Local Persistence**: State is preserved seamlessly in the browser via the HTML5 `localStorage` API.

---

## 🛠️ Technology Stack

- **Markup**: Semantic HTML5 with accessibility attributes (`aria-labels`, accessible forms, dialogs)
- **Styling**: Vanilla CSS3 with custom properties (CSS variables), glassmorphism, responsive grid & flexbox layouts, smooth cubic-bezier transitions, and mobile-first media queries
- **Typography**: Google Fonts — *Playfair Display* (Editorial headings) & *Plus Jakarta Sans* (Clean body typography)
- **Logic**: Modular Vanilla JavaScript (ES6+) with state management and LocalStorage data synchronization
- **Zero External Runtime Dependencies**: Instant loading, self-contained, and lightweight.

---

## 🚀 Getting Started

### Prerequisites
All you need is a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, Brave).

### Installation & Launch

1. **Clone the repository:**
   ```bash
   git clone https://github.com/03DxD12/charmstore.git
   cd charmstore
   ```

2. **Run locally:**
   - Simply double-click `index.html` to open it directly in your browser.
   - Or serve with any lightweight static server (e.g., VS Code Live Server, or Python):
     ```bash
     # Using Python 3
     python -m http.server 3000
     ```
   - Navigate to `http://localhost:3000` in your web browser.

---

## 📂 Project Structure

```text
charmstore/
│
├── index.html        # Complete Boutique Storefront, Builder, Cart, Tracking & Admin Dashboard
├── .gitignore        # Standard ignore rules for OS and IDE files
├── LICENSE           # MIT License
└── README.md         # Documentation and project overview
```

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

- **GitHub**: [@03DxD12](https://github.com/03DxD12)
- **Developer**: Denmhar Dimaculangan

Crafted with 💖 for jewelry lovers and boutique sellers.
