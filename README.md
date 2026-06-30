# 🛡️ SafePaws Admin V2.2

**Admin Dashboard for SafePaws Pet Services**
Manages Drivers, Vet Clinics, and Grooming Shops.

---

## ✨ Features
- **4-Tab Dashboard**: Drivers | Vets | Groomers | Earnings
- **Approval System**: Approve/Reject pending accounts with 1 click
- **Auto Commission Tracking**: 
    - Delivery: 15% 
    - Vet: 20% 
    - Grooming: 25%
- **Real-time KPIs**: Live revenue total from completed bookings
- **PWA Ready**: Installable on desktop and mobile

---

## 🚀 Setup & Deploy

### Step 1: Firebase Config
1.  Open `index.html` Line 58
2.  Paste your `firebaseConfig` 
3.  Paste your `ADMIN_EMAIL`

### Step 2: Create Admin Account
1.  Go to `Firebase Console > Authentication > Users`
2.  Click `Add user`
3.  Use the same email you put in `ADMIN_EMAIL`

### Step 3: Deploy to GitHub Pages
1.  Upload all 5 files to repo: `safepaws-admin`
2.  `Settings > Pages > Source: Deploy from a branch > main`
3.  `Settings > Visibility > Private` = Important if hard-coded email

---

## 📊 Firestore Collections Required
