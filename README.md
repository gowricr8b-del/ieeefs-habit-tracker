# Habit Tracker

A motivational habit tracker to help users build and maintain habits. Users can create habits with a frequency, mark daily completions, visualize their progress in a calendar, and track streaks.

This repo contains both the **frontend** (React + Vite + Tailwind) and **backend** (Node + Express + MongoDB) in a clean monorepo structure.

---

## Project Structure

```bash
habit-tracker/
│
├── client/ # Vite + React frontend
├── server/ # Node + Express + MongoDB backend
├── README.md
├── CONTRIBUTING.md
├── LICENSE
└── .github/ # Issue templates
```

---

## Features

- Add habits with frequency (daily, weekly, or custom interval)
- Mark habits complete for the day
- Calendar heatmap showing % completion per day
- Per-habit streaks
- Hover tooltips for day-wise progress

---

## Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- MongoDB instance (local or Atlas)

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

### Backend Setup

```bash
cd server
npm install
npm run dev
```

The backend will run on http://localhost:5000 by default.

Make sure to set your MongoDB connection string in .env:
```bash
MONGO_URI=your_mongodb_uri_here
PORT=5000
```

---

## Contributing

We love contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting any PRs or issues. It explains how to set up your environment, create branches, and contribute properly.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

