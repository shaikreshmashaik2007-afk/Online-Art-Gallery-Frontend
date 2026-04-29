<p align="center">
  <img src="https://img.shields.io/badge/Online%20Art%20Gallery-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=000000" alt="Online Art Gallery Frontend">
</p>

<h1 align="center">🎨 Online Art Gallery — Frontend</h1>
<p align="center">React (Vite) frontend for the Online Art Gallery platform</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/React-Vite-61DAFB?style=for-the-badge&logo=react&logoColor=000000" />
  <img src="https://img.shields.io/badge/Axios-HTTP%20Client-5A29E4?style=for-the-badge&logo=axios&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/React%20Router-Routing-CA4245?style=for-the-badge&logo=reactrouter&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/Deployed%20On-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=ffffff" />
</p>

---

## 🌐 Live Demo

- **Frontend (Vercel):** 👉 https://onlineartgallery.slayercore.me/


---

## 🧰 Tech Stack

| Layer | Technology |
|-------|------------|
| **Framework** | React (Vite) |
| **HTTP Client** | Axios |
| **Routing** | React Router DOM |
| **Notifications** | React Toastify |
| **Payment** | Razorpay (JS SDK) |
| **Deployment** | Vercel |

---

## ✨ Features

- 👤 **User Signup / Login with JWT Authentication**
- 🖼 **Browse Artworks** — explore the full gallery
- 🔒 **Protected Routes** — must be logged in to view or buy artwork
- 🛒 **Buy Now** — secure payments via Razorpay
- 👨‍💼 **Admin Panel** — add, edit, and delete artworks
- 📱 **Fully Responsive UI**

---

## 🖼️ Screenshots

### Home Page
> ![Home Page](public/home.png)

### Artworks Page
> ![Artworks Page](public/Artworks.png)

---

## ⚡ Local Setup

### Prerequisites

- Node.js v18+
- npm or yarn

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/shaikreshmashaik2007-afk/FSAD_ONLINE_ART_GALLERY_FRONTEND_AND_BACKEND.git

# 2. Navigate to the frontend folder
cd FSAD_ONLINE_ART_GALLERY_FRONTEND_AND_BACKEND/OnlineArtGallery-Frontend

# 3. Install dependencies
npm install

# 4. Create a .env file
cp .env.example .env
# Then edit .env with your values (see below)

# 5. Start the dev server
npm run dev
```

### Environment Variables

Create a `.env` file in the frontend root:

```env
VITE_API_BASE_URL=https://fsad-online-art-gallery-frontend-and.onrender.com
VITE_RAZORPAY_KEY_ID=rzp_test_xxxxxxxxxxxx
```

> For local backend testing, replace `VITE_API_BASE_URL` with `http://localhost:8080`

---

## 📁 Project Structure

```
OnlineArtGallery-Frontend/
├── public/
│   ├── home.png
│   └── Artworks.png
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/        # Axios API calls
│   ├── context/         # Auth context / JWT
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
└── vite.config.js
```

---

## 🚀 Deploying to Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your repo and set the **Root Directory** to `OnlineArtGallery-Frontend`
4. Add environment variables in Vercel dashboard:
   ```
   VITE_API_BASE_URL=https://fsad-online-art-gallery-frontend-and.onrender.com
   VITE_RAZORPAY_KEY_ID=your_razorpay_key
   ```
5. Deploy ✅

---

## 🔗 Related

- 📦 [Backend README](../OnlineArtGallery-Backend/README.md)
- 🌐 [Live Site](https://onlineartgallery.slayercore.me/)
