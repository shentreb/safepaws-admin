# 🛡️ SafePaws Admin V2.4
Admin Dashboard for SafePaws Pet Services. Manages Drivers, Vets, and Grooming Shops.
## ✨ Features
- 4-Tab Dashboard: Drivers | Vets | Groomers | Earnings
- Approval System: Approve/Reject pending accounts
- Search: Live search for all 3 tabs
- Earnings: Auto 15%/20%/25% commission + Date Filter
- PWA Ready: Installable + Offline + Opening Animation
## 🚀 Setup
1.  `index.html Line 111`: Paste `firebaseConfig.apiKey`
2.  `index.html Line 113`: Paste your `ADMIN_EMAIL`
3.  Firebase Console > Auth > Add user with that email
4.  Upload 5 files > Repo Settings > Pages > Deploy from main
## 📊 Firestore Collections Required
`drivers, vets, groomers, bookings, vet_bookings, grooming_bookings`
Bookings must have `status: "completed"` and `createdAt` field.
