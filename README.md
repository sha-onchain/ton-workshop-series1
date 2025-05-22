## Overview

This assignment walks you through (1) creating a Toncoin wallet and (2) submitting a GitHub pull request to add your address to `wallets.txt`. In your PR description, you’ll also explain custodial vs. non-custodial wallets.

---

## 🎥 Tutorials

- **Wallet Setup:** How to Create and Start Using Your First TON Wallet ([Video 1]( https://www.youtube.com/watch?v=JBQwce0wYIw  )) ([Video 2]( https://x.com/Shyaamal1108/status/1904006702250504445 )) 
- **Pull Request:** Creating a Pull Request : ([GitHub Docs](https://docs.github.com/articles/creating-a-pull-request ))

---

## 📝 Instructions

### 1. Create Your Toncoin Wallet

Choose one of these non-custodial options and follow the wallet video:

- **Tonkeeper (mobile & extension):** Download from ton.org and secure your 24-word seed phrase ([TON Blog](https://blog.ton.org/how-to-create-and-start-using-wallet "How to create and start using your first TON wallet?"))
- **@wallet Bot (in Telegram):** Zero-install, in-chat wallet powered by TON Connect ([The Open Network](https://docs.ton.org/v3/guidelines/ton-connect/wallet "Connect a wallet | The Open Network"))
- **Web Wallet (wallet.ton.org):** Browser-based, secret-phrase backup ([TON](https://ton.org/wallets "Get a wallet - TON"))

### 2. Fork & Clone the Repo

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
git checkout -b add-your-wallet

```

_Fork first via GitHub UI, then clone locally._ ([The GitHub Blog](https://github.blog/developer-skills/github/beginners-guide-to-github-creating-a-pull-request/ "Beginner's guide to GitHub: Creating a pull request"))

### 3. Add Your Wallet Address

- Open `wallets.txt`
- Append a new line in the format:
EQDkYCBG1mW7nMCJVaCBKd6X66ZzZyiyXUgAKbHkIKlwzdVq

### 4. Define Wallet Types in PR Description

In your PR body, answer:

1.  **What is a custodial wallet?**  
Custodial wallets are wallets where a third party holds your private keys and is responsible for managing and securing your assets

2.  **What is a non-custodial wallet?**  
Non-custodial wallets allow users to own and manage their private keys, providing complete control over their cryptocurrencies


### 5. Commit & Push Changes

```bash
git add wallets.txt
git commit -m "Add my Toncoin wallet address and explain wallet types"
git push origin add-your-wallet

```

### 6. Create the Pull Request

- Navigate to your fork on GitHub
- Click **Compare & pull request**
- Select **main** as the base branch and your branch as the compare branch
- Paste your wallet entry and wallet-type answers into the PR description
- Click **Create pull request** ([GitHub Docs](https://docs.github.com/articles/creating-a-pull-request "Creating a pull request - GitHub Docs"))

---

## ✅ Next Steps

Once submitted, your PR will be reviewed and merged—welcome to the TON ecosystem!

---

_Happy coding!_
