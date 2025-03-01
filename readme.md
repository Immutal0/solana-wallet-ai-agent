# 🚀 Solana Wallet AI Agent

An AI-powered Solana wallet management assistant built with **Next.js, Tailwind, GPT-4o-mini, and TypeScript**.  
This wallet agent allows users to execute Solana transactions and manage assets using natural language commands.

## 🌟 Features
- **Send SOL** → Transfer SOL to another wallet.
- **Create Token** → Create a new SPL Token using **Token-22** program.
- **Check Balance** → Get the current SOL balance.
- **Get Address** → Retrieve the public wallet address.
- **Transaction Status** → Fetch the latest transaction status.
- **Recent Transactions** → View the last 5 transactions.
- **AI-Powered Execution** → Transactions are executed by an AI agent.

## 🚀 Tech Stack
- **Frontend**: Next.js, TailwindCSS, TypeScript  
- **AI Integration**: GPT-4o-mini (OpenAI API)  
- **Solana SDK**: `@solana/web3.js`  
- **Solana Agent Kit**: `solana-agent-kit`
- **Deployment**: Vercel  

## 📜 Available Commands
| Command | Description | Example Prompt |
|---------|------------|---------------|
| **send** | Transfer SOL to a wallet | `Send 0.1 SOL to Ahafvp8nc3PXVwRMjgwhH7BYAyATKrGy38rvZ2AjduFg` |
| **create_token** | Create a new SPL Token | `Create Token Named GOKU` |
| **check_balance** | Get wallet balance | `Check my SOL balance` |
| **get_address** | Retrieve public key | `What is my wallet address?` |
| **transaction_status** | Get latest transaction status | `What happened to my last transaction?` |
| **recent_transaction** | Show last 5 transactions | `Show me my last 5 transactions` |

🔴 **Limitations**:
- **Buy and Swap** commands are **not yet supported**.
- **Free-tier GPT-4o-mini** has **token limitations**.

---

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Immutal0/solana-wallet-ai-agent.git
cd solana-wallet-ai-agent
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables  
Create a `.env.local` file and add the following:
```plaintext
SOLANA_PRIVATE_KEY="YOUR_PRIVATE_KEY_HERE"
SOLANA_RPC_URL="https://api.devnet.solana.com"
OPENAI_API_KEY="YOUR_OPENAI_API_KEY"
```
🚨 **DO NOT expose private keys!** Never use `NEXT_PUBLIC_` for sensitive values.

### 4️⃣ Run the Development Server
```sh
npm run dev
```
Visit **`http://localhost:3000`** to access the AI Wallet Agent.

---

## 🎯 Future Improvements
- ✅ Support **Buy & Swap** commands.
- ✅ Integrate **WalletConnect** for seamless transactions.
- ✅ Upgrade to **GPT-4o Pro** for better response accuracy.
- ✅ Add **NFT management** (minting, transferring, viewing).

---

👨‍💻 **Developed by [Immutal0](https://x.com/Immutal0)**  
💬 Have questions? Open an **issue** or reach out!  

---

🚀 **Star this repo if you find it useful!** 🌟  
