# 🏷️ PrimeBid – Online Auction Platform

**PrimeBid** is a full-featured online auction platform built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It allows users to list items for auction, place real-time bids, and manage auctions through an intuitive interface.

---

## 🚀 Features

- 🧑‍💼 Role-based access (Admin, Seller, Bidder)
- ⏱️ Real-time bidding with countdown timers
- 🛒 Auction item listing & management
- 🥇 Automatic winner declaration
- 🔒 Secure authentication & authorization
- 📊 Admin dashboard for monitoring users and auctions

---

## 🛠️ Tech Stack

| Technology  | Purpose                         |
|-------------|----------------------------------|
| MongoDB     | Database                        |
| Express.js  | Backend framework               |
| React.js    | Frontend library                |
| Node.js     | Backend runtime                 |
| Socket.IO   | Real-time communication         |
| JWT         | Authentication                  |
| TailwindCSS | UI Styling                      |

---

## 🧑‍💻 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Umeshhhmali/Prime-Bid.git
cd Prime-Bid
```

### Frontend Setup

```bash
cd client
npm install
npm start
```

### Backend Setup

```bash
cd server
npm install
npm run dev
```

> Make sure MongoDB is running on your local machine or update the `.env` file with your database URI.

---

## ⚙️ Environment Variables

Create a `.env` file in the `server/` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 📚 Folder Structure

```
PrimeBid/
│
├── client/          # React frontend
├── server/          # Node.js + Express backend
├── .env             # Environment variables
├── README.md
```

---

## 🙌 Contributing

1. Fork the repo
2. Create a new branch: `git checkout -b feature/yourFeature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/yourFeature`
5. Open a Pull Request

---
