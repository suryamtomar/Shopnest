# Shopnest — Full-Stack Ecommerce Platform (MERN)

A full-stack MERN e-commerce platform simulating a real-world online shopping experience — from product discovery to order tracking.

## Features

- **Product Grid with Live Search** — browse and filter products instantly
- **Persistent Cart** — cart state shared and saved across pages
- **Multi-item Checkout** — 3 dynamic delivery-date pricing tiers, real-time shipping cost updates, automated 10% tax calculation feeding a live order-total summary
- **Order History** — view all past orders with details
- **Visual Order Tracking** — progress bar (Preparing → Shipped → Delivered)
- **Custom Branding** — nest-and-leaf logo, green theme, favicon & responsive header across desktop/mobile

## Tech Stack

**Frontend:** React.js, CSS, Axios
**Backend:** Node.js, Express.js (RESTful API)
**Database:** MongoDB
**Planned Deployment:** Vercel (client), Render (server), MongoDB Atlas

## Screenshots

<img src="./Home.png" width="700"/>
<br>
<b>Home / Product Grid</b>

<br><br>

<img src="./checkout.png" width="700"/>
<br>
<b>Checkout</b>

<br><br>

<img src="./orders.png" width="700"/>
<br>
<b>Your Orders</b>

<br><br>

<img src="./track.png" width="700"/>
<br>
<b>Order Tracking</b>
## Project Structure
Shopnest/
- client/   → React frontend
- server/   → Express + MongoDB backend
- README.md

## Getting Started

```bash
git clone https://github.com/suryamtomar/Shopnest.git
cd Shopnest

# frontend
cd client
npm install
npm run dev

# backend (in a new terminal)
cd server
npm install
npm run dev
```

## Status

🚧 In active development — deployment coming soon.

## Author

**Suryam Tomar**
[suryamtomar.in](https://suryamtomar.in) · [GitHub](https://github.com/suryamtomar)
