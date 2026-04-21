# ⚾ MLB Player Statistics Dashboard

A real-time MLB statistics web application built with React and Firebase. Track game scores, standings, player rankings, and follow your favorite players all in one place.

---

## 📸 Screenshots

<img width="800" alt="image" src="https://github.com/user-attachments/assets/3945c354-59b2-4bb3-b061-5663cfa4c62a" />

<img width="800" alt="image" src="https://github.com/user-attachments/assets/452dc55c-4788-4db1-877a-1c9b992e5776" />

---

## ✨ Features

- **Live Game Scores** — Real-time scoreboard powered by the MLB Stats API
- **Standings** — Up-to-date division and league standings
- **Player Rankings** — Leaderboards for key batting and pitching stats
- **Player Search** — Search any MLB player and view their detailed stats
- **Follow Players** — Save and track your favorite players with a personalized list
- **News Feed** — Latest MLB news and updates
- **User Authentication** — Sign up / log in via Firebase Auth
- **Responsive Design** — Fully responsive UI that works on desktop and mobile

---

## 🛠 Tech Stack

| Category       | Technology                          |
|----------------|--------------------------------------|
| Frontend       | React, JavaScript, HTML, CSS         |
| Backend / DB   | Firebase Firestore, Firebase Auth    |
| API            | MLB Stats API (Official)             |
| Deployment     | _(e.g., Vercel / Netlify — add if applicable)_ |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- A Firebase project ([create one here](https://console.firebase.google.com/))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/mlb-dashboard.git
   cd mlb-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and add your Firebase config:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## 📁 Project Structure

```
mlb-dashboard/
├── public/
├── src/
│   ├── components/
│   │   ├── GameScores/
│   │   ├── Standings/
│   │   ├── Leaderboard/
│   │   ├── PlayerDetail/
│   │   ├── NewsFeed/
│   │   └── Auth/
│   ├── firebase/
│   ├── pages/
│   ├── hooks/
│   ├── App.js
│   └── index.js
├── .env
└── package.json
```

> _Update this to match your actual folder structure_

---

## 🔌 API Reference

This project uses the **[MLB Stats API](https://statsapi.mlb.com/api/)** — the official MLB data source.

Key endpoints used:
- `GET /api/v1/schedule` — Live and scheduled game data
- `GET /api/v1/standings` — League and division standings
- `GET /api/v1/stats/leaders` — Player stat leaderboards
- `GET /api/v1/people/{playerId}` — Individual player details

---

## 🔮 Future Improvements

- [ ] Add dark mode toggle
- [ ] Push notifications for followed players' game results
- [ ] Historical stats and season-over-season comparison
- [ ] Team-level stats page

---

## 👤 Author

**Wan Kim**
- LinkedIn: [linkedin.com/in/wankim-dev](https://linkedin.com/in/wankim-dev)
- Email: Wan.Kim@UTDallas.edu

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
