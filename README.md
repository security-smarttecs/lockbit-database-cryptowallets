# LockBit Database Dump – Crypto Wallets

This repository contains all Bitcoin wallets included in the LockBit database leak from May 2025.

Basic analyses have already been performed, such as determining the current balance and the total amount of Bitcoin that has actually been transferred through these wallets.

A brief explanation of the files:

* **wallet.json**: Contains all wallets from the `btc_addresses` table.  
* **wallet_advid.json**: Contains all wallets from the `btc_addresses` table, with each wallet mapped to the affiliate ID of the LockBit affiliate who used it.  
* **wallet_advid_nonzero.json**: Contains all wallets from the `btc_addresses` table, with each wallet mapped to the affiliate ID of the LockBit affiliate who used it, and only those wallets on which there was transaction activity.  

* **wallet.json**: Contains all wallets that were generated during the registration process for the joining fee.  
* **wallet_advid.json**: Contains all wallets generated during the registration process for the joining fee, and only those wallets on which a payment was received to cover the membership fee.  

These data may be used by anyone for their own research purposes. A mention would be appreciated.  
You can find our own brief analysis of the LockBit database leak here:

* v[https:/smarttecs.com/posts/2025-002-lockbit-database-analysis/](https:/smarttecs.com/posts/2025-002-lockbit-database-analysis/)