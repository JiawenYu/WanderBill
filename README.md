<div align="center">

# ✈️ WanderBill - Travel Expense Tracker

**Simplify shared travel expenses and settle debts effortlessly.**

![Platform](https://img.shields.io/badge/Platform-Web-blue)
![Storage](https://img.shields.io/badge/Storage-LocalStorage-orange)
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)

[Open WanderBill](https://jiawenyu.github.io/WanderBill/) 

---
</div>

## 📖 Introduction
WanderBill is a simple, browser-based expense tracking tool designed for travel groups. It helps you and your travel companions track shared expenses and simplifies complex debt settlements into minimal transactions.

## 🌟 Why WanderBill?

* 🚫 **Ad-Free Experience**: No interruptions, just tracking.
* 💡 **User-Friendly**: A clean, intuitive interface designed for everyone.
* 🆓 **100% Free**: No hidden fees or 'premium' locks.
* 🛡️ **Privacy-First**: Your data is stored locally in your browser, ensuring total privacy.

## ✨ Features

* 👤 **User Management**
  - Simple username-based login.
  - All data stored locally in your browser (no account needed).
* 📂 **Travel Group Management**
  - Create multiple travel groups.
  - Add/remove members to groups.
  - Delete groups when the trip is over.
* 💰 **Bill Tracking**
  - Add bills with description, currency, and amount.
  - **Equal split**: Automatically divides bill equally among all members.
  - **Custom split**: Specify exact amount for each member.
  - Date and time tracking for every expense.
* 🔄 **Debt Simplification**
  - Automatically calculates 'who owes whom.'
  - Reduces complex debt networks to minimal transactions.
  - *Example: If A owes B $100, and B owes C $200 → A pays C $100, B pays C $100.*
* 💱 **Currency Support**
  - Supports USD, EUR, GBP, JPY, CNY, KRW, THB, INR, AUD, CAD.
  - Automatic currency symbol display.

---

## 🚀 How to Use

### 1️⃣ First Time Setup
1. Open [WanderBill](https://jiawenyu.github.io/WanderBill/) in your web browser.
2. Enter your **username** (any name you prefer).
3. Click **'Start Tracking'**.

### 2️⃣ Managing Groups
- Go to the **Travel Groups** tab and click **'Create Group'**.
- Click **'View'** on a group to add your travel companions' usernames.

### 3️⃣ Adding Bills
- Go to the **Bills** tab and select your group.
- Fill in the details (Description, Amount, Split Type) and click **'Add Bill'**.

### 4️⃣ Settling Debts
- Go to the **Debts** tab to see the simplified transactions needed to settle all accounts.

---

## 💾 Data Storage & Privacy

> [!IMPORTANT]
> **WanderBill stores all data LOCALLY in your browser's `localStorage`.**
> * No data is ever sent to a server.
> * Data persists between browser sessions.
> * **To clear data:** Use your browser's 'Clear Site Data' option or logout.

---

## 🔄 Data Synchronization

Since WanderBill is local-first, follow these steps to sync data between devices:

### How to Sync
1. **Designate a 'Data Master'**: One person manages the master copy.
2. **Export Data**: Go to the **Data Sync** tab, click **'Export Data'**, and copy the JSON text.
3. **Share**: Send the JSON via messaging apps (Messenger, WhatsApp, etc.).
4. **Import**: Others go to the **Data Sync** tab, paste the JSON, and click **'Import Data'**.

### 💡 Best Practices
* **Sync regularly**: At least once a day during the trip.
* **Backup**: Export before making major changes.
* **Consistency**: Ensure usernames match exactly across all devices.
* **Merging**: Importing *adds* to existing data rather than replacing it.

---

<div align="center">

**Enjoy your trip and happy expense tracking! ✈️💰**

</div>
