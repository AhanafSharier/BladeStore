# Blade Store V4

Blade Store V4 is a lightweight Node.js-based digital store system featuring an admin panel, product/pricing control, promo codes, and JSON-file storage.  
It is fully responsive and works on all devices — mobile, tablet, and desktop.  
Designed for easy self-hosting without any external database.

---

## 🚀 Features

### 🛒 Store System
- Supports digital product listings  
- Pricing managed via `data/pricing.json`  
- Promo codes with validation (`data/promos.json`)  
- Order handling via JSON (`data/orders.json`)  
- Simple, clean, responsive UI

### 🔐 Admin System
- Admin login stored in `data/admins.json`
- Admin panel for:
  - Viewing orders
  - Managing pricing
  - Managing promotions

### ⚡ Backend (Node.js)
- Minimal Express.js server (`server.js`)
- JSON file–based storage (no SQL or external DB)
- Auto-reload of pricing/promos/orders from disk

### 📱 Frontend
- HTML/CSS/JS based
- Fully responsive design (mobile → PC)
- Smooth UI and instant updates (no page reloads)

---

## 📂 Project Structure

```
Blade_StoreV4/
│
├── server.js                # Node.js backend server
├── package.json             # Dependencies
├── package-lock.json
│
├── data/
│   ├── admins.json          # Admin accounts
│   ├── orders.json          # Orders database
│   ├── pricing.json         # Product prices
│   └── promos.json          # Promo codes
│
└── node_modules/            # Installed packages
```

---

## 🛠️ Installation & Setup

### 1️⃣ Install Dependencies
```bash
npm install
```

### 2️⃣ Start the Server
```bash
node server.js
```

### 3️⃣ Open in Browser
```
http://localhost:3000
```

---

## 📦 Data Files

### `admins.json`
Stores admin login information.

### `pricing.json`
Controls product price values.

### `promos.json`
Coupon codes & discounts.

### `orders.json`
Every order placed is added here.

All data is stored locally — no external database.

---

## 🧪 Development

To modify UI:
- Edit HTML/CSS/JS files inside the frontend folder (if included)
- Customize JSON files for pricing/promos
- Modify `server.js` to extend APIs or add endpoint logic

---

## 📝 License
This project is released publicly for educational and commercial customization.  
You may modify and use it in your own store.

---

## ❤️ Credits
Developed as Blade Store by Me for people to use — optimized and improved for modern devices and easy hosting.
