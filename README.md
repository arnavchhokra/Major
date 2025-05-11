
# 🧑‍💻 Decentralized Data Labelling  Platform

A decentralized marketplace built on the **Solana blockchain** that connects freelancers with clients, with a focus on **image labeling and comparison** tasks.

---

## 🚀 Features

* **Wallet Integration**: Secure authentication using Solana wallets
* **Task Management**: Create and complete image comparison tasks
* **Payment System**: Automated payments using Solana (SOL)
* **Dual Interface**: Separate frontends for task creators and workers

---

## 📁 Project Structure

```
/backend
/frontend-user
/frontend-worker
```

---

## 🛠 Technology Stack

### Frontend

* Next.js 14
* React
* TailwindCSS
* Solana Wallet Adapter

### Backend

* Node.js
* Express
* PostgreSQL
* Prisma ORM

### Blockchain

* Solana
* Web3.js

---

## 💻 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/decentralized-fiverr.git
   cd decentralized-fiverr
   ```

2. **Install dependencies:**

   ```bash
   cd backend && npm install
   cd ../frontend-user && npm install
   cd ../frontend-worker && npm install
   ```

3. **Set up environment variables:**

   * **Backend `.env`:**

     ```
     DATABASE_URL=your_postgres_connection_url
     JWT_SECRET=your_jwt_secret
     ```

   * **Frontend `.env.local`:**

     ```
     NEXT_PUBLIC_SOLANA_NETWORK=devnet
     ```

---

## 🚀 Running the Project

* **Start the backend**

  ```bash
  cd backend && npm run dev
  ```

* **Start the user frontend**

  ```bash
  cd frontend-user && npm run dev
  ```

* **Start the worker frontend**

  ```bash
  cd frontend-worker && npm run dev
  ```

---

## 📝 API Documentation

* **Authentication**
* **Tasks**
* **Submissions**

---

## 💰 Payment System

| Action        | Amount   |
| ------------- | -------- |
| Task Creation | 0.1 SOL  |
| Worker Reward | 0.05 SOL |
| Platform Fee  | 0.01 SOL |

---

## 🔐 Security Features

* Wallet signature verification
* JWT authentication
* Rate limiting
* Input validation
* Transaction verification

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch:

   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add some amazing feature"
   ```
4. Push to the branch:

   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE.md](LICENSE.md) file for details.

---

## 👥 Team

* **Project Lead** - \[Name]
* **Backend Developer** - \[Name]
* **Frontend Developer** - \[Name]
* **Smart Contract Developer** - \[Name]

---

## 📞 Support

For support, email: [support@decentralized-fiverr.com](mailto:support@decentralized-fiverr.com)
Or join our **Discord** channel.

---

**Note**: Replace all placeholder values (like `[Name]`, database URLs, secrets, etc.) before deploying.

---

