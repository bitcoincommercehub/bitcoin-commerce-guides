# Guide 01: Accepting Non-Custodial Bitcoin & Lightning Payments

This guide helps solo digital creators, freelancers, and online sellers start accepting Bitcoin payments without third-party payment processors or KYC bottlenecks.

## 1. Choose Your Payment Addresses
To support both small micro-tips ($1–$20) and larger orders without fee friction, set up two complementary payment methods:
- **Lightning Address (for instant micro-payments):** Use a non-custodial or fast-setup Lightning wallet (such as Phoenix, Breez, or Speed Wallet) to generate an email-style address like `yourname@domain.com`.
- **Native SegWit On-Chain Address (`bc1q...`):** Use an open-source wallet (such as Sparrow, Electrum, or BlueWallet) and always select **Native SegWit (Bech32)** starting with `bc1q` for lower network fees and universal compatibility.

## 2. Best Practices for Checkout Pages
- Display a clean QR code alongside a one-click copyable text address.
- Clearly state which networks are supported (Bitcoin Mainnet vs. Lightning Network) to prevent accidental cross-chain transfers.
- Include a short 2-line note for first-time crypto buyers explaining how to use instant swap tools if they hold other assets.

## 3. Security & Backup Checklist
- [ ] Write down your 12 or 24-word recovery seed phrase offline on paper or metal.
- [ ] Never store seed phrases in cloud notes, screenshots, or unencrypted text files.
- [ ] Test receiving a small amount ($1) before sharing your payment page publicly.
