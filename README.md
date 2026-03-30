# 🖨️ Press Orders — Order Book for Print Shops

> A streamlined order management system built for printing businesses — track jobs, manage payments, and deliver on time.

---

## 📸 Preview

![Press Orders Dashboard](./screenshot.png)

---

## ✨ Features

- **Order Tracking** — Create and manage print orders from intake to delivery
- **Order Types** — Supports Wedding Cards, Receipt Books, Binding, Certificates, Report Cards, Magazines, and more
- **Status Views** — Quickly filter orders by Pending, Ready to Deliver, or Unpaid
- **Payment Management** — Track advance payments and outstanding balances per order
- **Order Workflow** — One-click "Start Work" to move orders into progress
- **Search & Filter** — Search by customer name; filter by order type, delivery status, and payment status
- **Dashboard Stats** — At-a-glance cards for Total Orders, In Progress, Unpaid Amount, and Ready to Deliver

---

## 🗂️ Order Statuses

| Status | Description |
|---|---|
| **Pending** | Order received, work not yet started |
| **In Progress** | Actively being worked on |
| **Ready to Deliver** | Completed and awaiting pickup/delivery |
| **Unpaid** | Payment not yet received |

---

## 🧾 Supported Order Types

- Wedding Cards
- Receipt Books
- Binding
- Certificates
- Report Cards
- Magazines
- Other

---

## 🚀 Getting Started

### Prerequisites

- Node.js `v18+`
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/press-orders.git

# Navigate into the project
cd press-orders

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:3000`.

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React / Next.js |
| Styling | Tailwind CSS |
| State | React Context / Zustand |
| Database | (your DB here, e.g. Supabase / Firebase) |
| Hosting | (e.g. Vercel / Netlify) |

> Update the table above to reflect your actual stack.

---

## 📁 Project Structure

```
press-orders/
├── components/         # Reusable UI components
│   ├── OrderCard.jsx
│   ├── Sidebar.jsx
│   └── StatsBar.jsx
├── pages/              # App routes
│   ├── index.jsx       # All Orders view
│   └── orders/[id].jsx # Order detail
├── lib/                # Utilities and helpers
├── styles/             # Global styles
└── public/             # Static assets
```

---

## 📋 Usage

1. Click **+ New Order** to create a print job
2. Fill in customer name, order type, quantity, and payment details
3. Orders appear in **All Orders** and the relevant type/status sidebar
4. Click **Start Work** to move an order to *In Progress*
5. Mark orders as **Ready** when complete and **Paid** once payment is received

---

## 🛣️ Roadmap

- [ ] Order detail / edit page
- [ ] Invoice & receipt generation (PDF)
- [ ] WhatsApp notification to customer on order ready
- [ ] Multi-user / staff role support
- [ ] Analytics dashboard (monthly revenue, order volume)
- [ ] Mobile app (React Native)

---

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Commit your changes
git commit -m "feat: add your feature"

# Push and open a PR
git push origin feature/your-feature-name
```

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 👤 Author

Built with ❤️ for print shop owners.  
Have questions or feedback? [Open an issue](https://github.com/your-username/press-orders/issues) or reach out directly.
