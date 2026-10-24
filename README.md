# ☕ Velvet Roast — Artisanal Coffee & Roastery (Full-Stack Web Application)

A modern 2026 editorial full-stack cafe website with an interactive customer experience, custom drink builder, floor-plan table reservation engine, live order tracker, and an integrated **Admin POS & Kitchen Display System (KDS)**.

## ✨ Key Features
1. **2026 Editorial Bento Grid & Sensory Design**: Warm Oat Milk (`#FAF6F0`), Deep Espresso (`#1C1613`), Terracotta Copper (`#C86D51`), and Forest Matcha (`#2D4A3E`) with instant Dark/Light Roastery Mode toggle.
2. **Interactive Custom Drink Studio**: Customize cup size, plant/dairy milk (Oat, Almond, Barista Whole), sweetness level, espresso roast, and toppings with real-time price and calorie calculation.
3. **AI Flavor Sommelier ("Find Your Perfect Brew")**: Mood + flavor profile matcher that recommends the ideal drink and adds it directly to your cart.
4. **Interactive Floor-Plan Table Booking**: Visual cafe layout with 8 distinct seating zones (Sunlight Window Nook, Garden Glasshouse, Co-Working Power Booth, Acoustic Lounge, etc.) showing live availability, seat capacity, and power outlets.
5. **Live Order Tracker & Coupon Checkout**: Supports promo codes (`VELVET20` for 20% off, `FIRSTBREW` for ₹100 off), Dine-In / Takeaway / Delivery modes, and a 4-stage live progress bar.
6. **Full-Stack Admin POS & Live REST API Console**:
   - **Kitchen Display System (KDS)**: Advance live orders (`Received` → `Brewing` → `Quality Check` → `Ready`).
   - **Menu & Inventory Manager**: Toggle `In Stock` / `Sold Out` status or add new seasonal items live.
   - **Live API Inspector**: Inspect every `GET`, `POST`, and `PATCH` request/response payload in real time.

## 🚀 How to Run Locally (Node.js + Express Backend)

1. Extract `velvet_roast_fullstack.zip` and open the folder in your terminal:
   ```bash
   cd velvet-roast-fullstack
   npm install
   npm start
   ```
2. Open `http://localhost:3000` in your browser.
3. All API routes (`/api/menu`, `/api/orders`, `/api/reservations`, `/api/stats`) read and write to `data/database.json`.
