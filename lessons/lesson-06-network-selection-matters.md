---
module: 2
lesson_number: 6
course: first-crypto-steps
---

## 🎧 Lesson Podcast
{% embed url="https://storage.googleapis.com/first-crypto-steps-media/lesson-06/audio/lesson6%20Don_t_Lose_Crypto_to_the_Wrong_Network.m4a" %}

## 🎬 Video Overview
{% embed url="https://storage.googleapis.com/first-crypto-steps-media/lesson-06/video/lesson6%20Choosing_the_Right_Crypto_Network.mp4" %}

# Lesson 6: Network Selection Matters

![Header](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_06/first-crypto-steps_06_header.png)


**Core concept:** Choosing the right network is like choosing the right delivery service—send via the wrong one and your package never arrives.

---

## Choosing the Right Delivery Service
![Inline Analogy](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_06/first-crypto-steps_06_inline_analogy.png)


You want to ship a package. You can choose:
- **FedEx** (fast, works everywhere in their network)
- **UPS** (different network, doesn't deliver to FedEx locations)
- **Local courier** (only works in your city)

If you ship FedEx but give a UPS-only pickup location, the package can't be delivered.

Blockchain networks work similarly. A transaction on Ethereum only arrives at Ethereum addresses. Sending the "same" token via the wrong network can mean permanent loss.

---

## The Same Token, Different Networks
![Infographic](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_06/first-crypto-steps_06_infographic.png)


Here's where confusion happens:

**USDC (a stablecoin) exists on:**
- Ethereum (original)
- Polygon
- Arbitrum
- Solana
- Many others

The token has the same name and value, but each version lives on a different blockchain.

If you send USDC via Polygon to an exchange that only accepts USDC via Ethereum, you might lose those funds forever. The tokens exist, but on a network the recipient can't access.

---

## How Network Selection Appears

When withdrawing from exchanges, you'll see network choices:

**Example withdrawal screen:**
```
Withdraw ETH

Network: [Select network ▼]
- Ethereum (ERC20)
- Arbitrum One
- Optimism
- Polygon
- BSC

Address: [Enter recipient address]
Amount: [Enter amount]
```

Each option has different:
- **Fees:** Ethereum often most expensive, L2s cheaper
- **Speed:** Some faster than others
- **Compatibility:** Not all destinations support all networks

**You must match the network** to what the receiving wallet/exchange supports.

---

## Checking What Networks Are Supported

Before sending:

**If sending to an exchange:**
Check their deposit page for that specific crypto. It will list supported networks. Only use those networks.

**If sending to your own wallet:**
Check what networks your wallet app supports. Most support Ethereum and popular L2s, but verify.

**If sending to someone else:**
Ask them which network they want to receive on.

Never assume. Always verify.

---

## What Happens With Wrong Network

**Scenario 1: Exchange doesn't support the network**
You send USDC via Polygon to Coinbase, which only accepts Ethereum USDC.
- Funds arrive at the address
- But Coinbase doesn't monitor Polygon
- Your funds sit there inaccessible
- Recovery sometimes possible (expensive, not guaranteed)

**Scenario 2: Wallet doesn't support the network**
You send tokens via Arbitrum to a wallet that doesn't support Arbitrum.
- If you control the wallet keys, you can add the network and access funds
- If you don't control keys (like an exchange), might be lost

**Scenario 3: Incompatible chains entirely**
You try to send Bitcoin to an Ethereum address (or vice versa).
- Transaction usually fails before sending (different address formats)
- But some edge cases can result in loss

---

## Network Selection Best Practices

**Always verify supported networks first:** Check both sending and receiving sides.

**Use matching networks:** If they support Ethereum, send via Ethereum. Don't get creative.

**Consider fees:** If multiple networks supported, cheaper networks save money.

**Test with small amount:** Especially for new networks or destinations.

**Read the warnings:** Exchanges show network warnings. Don't skip them.

**When in doubt, ask:** Contact support or ask the recipient before sending.

---


![Summary](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_06/first-crypto-steps_06_summary.png)

## Key Takeaways

- **Same tokens can exist on multiple networks**—USDC on Ethereum ≠ USDC on Polygon
- **Sender and receiver must use matching networks**—mismatches cause losses
- **Always check supported networks** on both ends before sending
- **Cheaper networks exist** but only use if supported by destination
- **Wrong network = potentially permanent loss**—transactions are irreversible
- **When uncertain, verify first**—no shame in asking or testing with small amounts
