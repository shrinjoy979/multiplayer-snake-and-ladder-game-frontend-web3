
![landing](https://github.com/user-attachments/assets/67457452-73c9-45a0-b0e5-33d3dc2676a1)
<img width="1440" alt="game-create-or-join" src="https://github.com/user-attachments/assets/0f7a4684-4764-4ebf-8bfc-e7303ff94368" />
<img width="1439" alt="account" src="https://github.com/user-attachments/assets/9604dd3f-86bd-4122-ae3a-b8bbb22f526d" />
![winner](https://github.com/user-attachments/assets/abe6255c-bfa9-49e5-a1ba-76c3e1cebbc1)

# 🐍 SnakesWin

**SnakesWin** is a real-time multiplayer Snake & Ladder betting game built on the **Solana blockchain**.

Players can join game rooms, place SOL bets, and compete against each other in real time. The winner receives the pooled winnings, while the platform takes a small fee from the profit.

🔗 **Live Demo:** https://snake-win.vercel.app/

🔗 **Frontend:** https://github.com/shrinjoy979/multiplayer-snake-and-ladder-game-frontend-web3

🔗 **Backend:** https://github.com/shrinjoy979/multiplayer-snake-and-ladder-game-backend

---

## 🎮 Features

* 🐍 Multiplayer Snake & Ladder gameplay
* 👥 Real-time game rooms
* 💰 SOL-based betting
* 🏆 Automatic winner payouts
* 🔗 Solana blockchain integration
* 📜 Transparent blockchain transactions
* ⚡ Real-time multiplayer communication
* 🔐 Wallet-based Web3 interactions

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Solana Web3.js
* Solana Wallet Adapter

### Backend

* Node.js
* Express
* Socket.IO
* PostgreSQL
* Prisma

### Blockchain

* Solana
* SOL
* Solana Web3.js

---

## 🏗️ Architecture

```text
                    ┌─────────────────────┐
                    │      Player         │
                    │   Connect Wallet    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │      + Vite         │
                    └──────────┬──────────┘
                               │
                     Socket.IO │
                               ▼
                    ┌─────────────────────┐
                    │   Node.js Backend   │
                    │     + Express       │
                    └──────┬──────┬───────┘
                           │      │
                  ┌────────┘      └─────────┐
                  ▼                         ▼
          ┌───────────────┐         ┌──────────────┐
          │  PostgreSQL   │         │    Solana    │
          │    + Prisma   │         │  Blockchain  │
          └───────────────┘         └──────────────┘
```

---

## 🎯 How It Works

1. Connect a Solana wallet.
2. Choose a betting amount.
3. Create or join a multiplayer game room.
4. Players place their SOL bets.
5. The game starts when the required players join.
6. Players compete in real time.
7. The winner is determined by the game logic.
8. The winner receives the pooled winnings.
9. The platform takes a small fee from the profit.
10. Transactions are recorded on the Solana blockchain.

---

## 💰 Betting & Payout

Players can participate using SOL.

The basic flow is:

```text
Player 1 ──┐
Player 2 ──┤
Player 3 ──┼──► Betting Pool ──► Winner
Player 4 ──┘                         │
                                    ▼
                              Platform Fee
```

The winner receives nearly **2× their bet amount**, depending on the number of players and platform fee structure.

> ⚠️ This project involves blockchain-based betting. Use only on supported networks and with funds you are comfortable risking.

---

## 🔗 Blockchain

SnakesWin uses **Solana** for handling SOL transactions.

Blockchain integration provides:

* Transparent transactions
* Wallet-based payments
* Verifiable transaction history
* Fast and low-cost transactions

---

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

* Node.js
* npm
* A Solana-compatible wallet such as Phantom
* Access to a Solana RPC endpoint

### Clone the repository

```bash
git clone https://github.com/shrinjoy979/multiplayer-snake-and-ladder-game-frontend-web3.git

cd multiplayer-snake-and-ladder-game-frontend-web3
```

### Install dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file based on `.env.example`.

```env
VITE_API_URL=your_backend_url
```

Add any additional Solana/RPC configuration required by your environment.

### Start the development server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 🔧 Backend

The backend is maintained in a separate repository:

https://github.com/shrinjoy979/multiplayer-snake-and-ladder-game-backend

The backend is responsible for:

* Multiplayer game state
* Game rooms
* Real-time communication
* Player management
* Game results
* Payment processing
* Database operations

---

## 📁 Project Structure

```text
multiplayer-snake-and-ladder-game-frontend-web3/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── utils/
│   └── ...
│
├── .env.example
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## 🌐 Live Demo

Try the game:

**https://snake-win.vercel.app/**

---

## 🗺️ Future Improvements

* Player leaderboard
* Match history
* Better matchmaking
* Tournament mode
* On-chain game settlement
* Improved anti-cheat mechanisms
* Mobile optimization
* Player statistics
* Transaction history dashboard
* Mainnet deployment

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/your-feature
```

3. Commit your changes.

```bash
git commit -m "Add your feature"
```

4. Push the branch.

```bash
git push origin feature/your-feature
```

5. Open a Pull Request.

---

## ⭐ Support

If you find **SnakesWin** interesting or useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is for educational and experimental purposes.

See the repository for license details.
