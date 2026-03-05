# WanderBill - Travel Expense Tracker

WanderBill is a simple, browser-based expense tracking tool designed for travel groups. It helps you and your travel companions track shared expenses and simplify debt settlements.

## Features

### 1. **User Management**
   - Simple username-based login
   - All data stored locally in your browser (no account needed)

### 2. **Travel Group Management**
   - Create multiple travel groups
   - Add/remove members to groups
   - Delete groups when trip is over

### 3. **Bill Tracking**
   - Add bills with description, currency, amount
   - Select payer from group members
   - Two split options:
     - **Equal split**: Automatically divides bill equally among all members
     - **Custom split**: Specify exact amount for each member
   - Date and time tracking for each expense

### 4. **Debt Simplification**
   - Automatically calculates who owes whom
   - Reduces complex debt networks to minimal transactions
   - Shows simplified payment instructions
   - Example: If A owes B $100, and B owes C $200 → A pays C $100, B pays C $100

### 5. **Currency Support**
   - USD, EUR, GBP, JPY, CNY, KRW, THB, INR, AUD, CAD
   - Automatic currency symbol display

## How to Use

### First Time Setup
1. Open `index.html` in your web browser
2. Enter your username (any name you prefer)
3. Click "Start Tracking"

### Creating a Travel Group
1. Go to the **Travel Groups** tab
2. Enter a group name (e.g., "Thailand Trip 2023")
3. Click "Create Group"
4. Click "View" on the group to add members

### Adding Members to a Group
1. In the group details view, enter a member's username
2. Click "Add Member"
3. Repeat for all travel companions

### Adding a Bill
1. Go to the **Bills** tab
2. Select the group from dropdown
3. Fill in bill details:
   - Description (e.g., "Dinner at restaurant")
   - Currency and amount
   - Who paid the bill
   - Split type (equal or custom)
   - Date and time
4. Click "Add Bill"

### Simplifying Debts
1. Go to the **Debts** tab
2. Select a group from dropdown
3. View simplified transactions needed to settle all debts

## Data Storage

- All data is stored **locally** in your browser's localStorage
- No data is sent to any server
- Data persists between browser sessions
- To clear data: Use browser's "Clear Site Data" option or logout

## Data Synchronization

Since WanderBill stores data locally, you need to synchronize manually when traveling with friends:

### How to Sync Data Between Devices

1. **One person manages the master copy** (usually the trip organizer)
2. **Export data after each update**:
   - Go to the **Data Sync** tab
   - Click "Export Data"
   - Copy the JSON text
3. **Share with others**:
   - Send the JSON via messaging app (Messenger, WhatsApp, Telegram, etc.)
4. **Others import the data**:
   - Go to the **Data Sync** tab
   - Paste the JSON text into the Import box
   - Click "Import Data"
   - All bills and groups will be updated

### Best Practices for Group Travel
- **Designate a "data master"** who updates bills and shares regularly
- **Sync at least once a day** during the trip
- **Export before making changes** if multiple people are updating
- **Use consistent usernames** across all devices
- **Import merges data**: Importing adds to your existing data (doesn't replace it)
- **Check usernames**: When importing, ensure your username matches exactly with group member names


---

Enjoy your trip and happy expense tracking! ✈️💰