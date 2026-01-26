---
course: first-crypto-steps
module: 2
lesson: 5
title: "Understanding Wallet Addresses"
description: "How to use and verify crypto addresses when sending or receiving"
---

# Understanding Wallet Addresses

![Header](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_05/first-crypto-steps_05_header.png)


**Core concept:** A wallet address is like a mailing address for money—it tells the network exactly where to send the funds.

---

## Mailing Address for Money

When you mail a letter, you write the address carefully:
- Street number and name
- City, State, ZIP code
- Country if international

Get any part wrong, and the letter goes to the wrong place or gets lost.

Crypto addresses work similarly—they tell the network where to send value:
- One wrong character = wrong destination
- There's no "return to sender"
- The "post office" (blockchain) delivers exactly what you addressed

The stakes are higher than letters: send crypto to a wrong address and it's usually gone forever.

---

## What Addresses Look Like

Different blockchains have different address formats:

**Bitcoin:**
```
bc1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh
```
- Starts with bc1, 1, or 3
- Case-sensitive
- 26-62 characters

**Ethereum (and EVM chains):**
```
0x71C7656EC7ab88b098defB751B7401B5f6d8976F
```
- Always starts with 0x
- Not case-sensitive (but mixed case provides checksum)
- Always 42 characters

**Solana:**
```
7xKXtg2CW87d97TXJSDpbD5jBkheTqA83TZRuJosgAsU
```
- Base58 encoded (no 0, O, I, l to avoid confusion)
- 32-44 characters

Knowing the format helps you verify you have the right type of address for your transaction.

---

## Getting Your Address to Receive

To receive crypto, you need to share your address with the sender:

**In wallet apps:**
1. Open your wallet
2. Find "Receive" or "Deposit"
3. Select the cryptocurrency
4. Copy the address or show QR code

**On exchanges:**
1. Navigate to "Wallet" or "Assets"
2. Find the specific crypto
3. Click "Deposit"
4. Copy the address shown

**Important:** Always use the copy button. Don't try to type addresses manually—too easy to make errors.

---

## Sending to an Address

To send crypto to someone else:

1. Get their address (they share it with you)
2. Open your wallet/exchange
3. Find "Send" or "Withdraw"
4. Paste the recipient address
5. Enter amount
6. Verify everything carefully
7. Confirm and send

**Critical verification:**
- Check first few characters match
- Check last few characters match
- Make sure it's the right network (more on this in next lesson)
- For large amounts, send a small test first

---

## Common Address Mistakes

**Sending to wrong address type:** Bitcoin address for Ethereum transaction = lost funds.

**Wrong network:** Same address format but different blockchain = lost funds (e.g., Ethereum mainnet vs. Polygon).

**Typos:** Even one character off = funds go nowhere or to wrong person.

**Clipboard malware:** Some malware swaps addresses when you copy/paste. Always verify after pasting.

**Old addresses:** Some services rotate addresses. Always get fresh address before sending.

Most of these result in permanent loss. Blockchain transactions are irreversible.

---

## Tips for Safe Addressing

**Always copy/paste:** Never manually type addresses.

**Verify after pasting:** Compare first 4-6 and last 4-6 characters with the original.

**Use QR codes when possible:** Eliminates copy/paste errors.

**Send test amounts:** For large transfers, send small amount first. Verify receipt. Then send the rest.

**Bookmark known addresses:** For frequent sends, save verified addresses.

**Double-check network:** Make sure you're using the right blockchain.

These habits might seem paranoid, but they prevent expensive mistakes.

---


![Summary](https://storage.googleapis.com/first-crypto-steps-media/images/lesson_05/first-crypto-steps_05_summary.png)

## Key Takeaways

- **Addresses are delivery destinations** for cryptocurrency—like mailing addresses for money
- **Different blockchains have different formats**—learn to recognize them
- **Always copy/paste, never type**—too easy to make character errors
- **Verify after pasting**—check first and last characters against original
- **Wrong address or network = permanent loss**—transactions are irreversible
- **Send test amounts first** for large transfers—small price for peace of mind
