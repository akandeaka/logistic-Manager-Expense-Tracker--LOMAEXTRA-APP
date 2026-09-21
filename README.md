# 💰 Business Finance Tracker

A lightweight, offline-first web app for tracking daily income, expenses, and profit across **four business activities**:

- ⛏️ **Mining** — buy/sell mineral transactions
- 🚗 **Bolt** — daily vehicle trip income (with fuel, commission, other expenses)
- 🎯 **Sports Investment** — ticket staking and payouts
- 💰 **Personal Income** — gift, refund, loan, family support, salary, sales
- 🧾 **Personal Expenses** — everyday spending

Built as a single-page Progressive Web App (PWA). Runs entirely in the browser. No server, no login, no cost.

**Live URL (GitHub Pages):** https://akandeaka.github.io/finance-tracker/
**Backup URL (Netlify):** https://akande-finance.netlify.app/

> Use whichever URL loads reliably on your network. Both serve the exact same app.

---

## ✨ Features

### ⛏️ Mining Business
- Track every mineral transaction by type (Tin, Columbite, Zircon, Monazite, Lead, Other)
- Auto-calculates profit: `Selling Amount − Purchase Cost − Other Expenses`
- Supports unsold stock (leave selling amount blank — profit shows as `—` until sold)

### 🚗 Bolt Business
- Record fuel cost, **Bolt commission**, other expenses, and multiple trip incomes per day
- Auto-calculates daily profit: `Total Passenger Income − Fuel − Bolt Commission − Other Expenses`
- Enter trip incomes as a comma-separated list: `2500, 3000, 1800, 2200`

### 🎯 Sports Investment
- Log each ticket: stake, odds, status (Won/Lost/Pending), optional manual payout
- Auto-calculates: `Profit/Loss = Payout − Stake`
- Tracks total invested, total won, total lost per period

### 💰 Personal Income
- Record money received personally (not from your businesses)
- Categories: 🎁 Gift · 💵 Refund · 🏦 Loan Received · 👨‍👩‍👧 Family Support · 💼 Salary / Personal Work · 🏪 Sale of Personal Item · 💰 Other
- Track source and notes per entry

### 🧾 Personal Expenses
- Categorized spending: Food, Transportation, Phone/Data, Household, Utilities, Health, Rent, Other
- One-tap logging

### 📊 Dashboard
- **Daily / Weekly / Monthly** summary views
- **Personal Cash Flow** card: Income − Expenses = Personal Net
- **Profit by Business** bar chart
- **7-day net trend** line chart
- **Monthly projection** based on recorded days
- **Smart insights**: best-performing business, reinvestment suggestion (50% rule), overspend warnings

### 💾 Data Safety
- All data stored in your browser's `localStorage` (private, no server)
- JSON backup export/import
- Works fully offline once installed as a PWA

---

## 📱 How to Install (PWA)

### Android
1. Open the app URL in **Chrome**
2. Tap ⋮ menu → **Install app** or **Add to Home screen**
3. Confirm — the app appears with its own icon

### iPhone
1. Open the app URL in **Safari**
2. Tap **Share** → **Add to Home Screen**

### Desktop (Chrome / Edge)
1. Open the app URL
2. Click the **install (⊕)** icon in the address bar

After installing, the app **works fully offline** — no internet needed for daily use.

---

## ⚠️ Network / VPN Note

**GitHub Pages (`akandeaka.github.io`) is intermittently blocked or throttled by some Nigerian ISPs** (MTN, Airtel, Glo, Spectranet). Symptoms:

- Browser shows `ERR_CONNECTION_TIMED_OUT`
- The URL works one minute, times out the next
- Works fine on mobile data but not WiFi (or vice versa)

### Workaround
If you can't reach the GitHub Pages URL:

1. **Use the Netlify URL instead** (see top of file) — usually not blocked
2. **Turn on a VPN** and reload
3. Once the app loads, **install it as a PWA** — after that, it runs from cache
4. Only use VPN when updating the app from the web

This is a network issue, **not a problem with the app itself**.

---

## 💾 Data Backup — Do This Weekly

Your data lives **only in this browser on this device**. It is not synced to any server.

**Every Sunday, do this:**

1. Open the app → **⚙️ Data** tab
2. Tap **⬇️ Export JSON Backup**
3. Save the file and send it to yourself on **WhatsApp** ("Message yourself")
4. Also save to Google Drive if possible

**To restore:**
1. Open the app → **⚙️ Data**
2. Tap **⬆️ Import Backup**
3. Select your JSON file → done

Keep the last **4 weekly backups** in case of emergency.

---

## 🗂️ Project Files
