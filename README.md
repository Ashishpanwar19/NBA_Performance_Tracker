🏀 NBA Player Performance Tracker
A responsive React/TypeScript application for analyzing NBA player statistics with interactive visualizations.
🔗 Live Demo: https://mellow-sprinkles-304f2a.netlify.app
✨ Features
Interactive Dashboard: Filter and sort players by stats (PPG, APG, RPG)
Player Comparison: Side-by-side stat comparison with charts
Dark Mode: Toggleable UI theme
Type-Safe: Built with TypeScript for robust typing
Optimized Build: Vite-powered fast refresh and bundling
🛠 Tech Stack
Core:

React 18 + TypeScript

Vite (Build Tool)

Tailwind CSS

State Management:

Context API (PlayerDataContext)

Data:

TypeScript Interfaces (Player.ts, mIModels.ts)

Sample Data (TshaPlayerData.ts)

Visualization:

Chart.js (via StatsChart.tsx)

📂 Project Structure
bash
project/
├── dist/                    # Production build
├── src/
│   ├── components/          # Reusable UI
│   │   ├── Navigation.tsx
│   │   ├── PlayerCard.tsx
│   │   ├── PlayersTable.tsx
│   │   └── StatsChart.tsx
│   ├── context/             # State management
│   │   └── PlayerDataContext.tsx
│   ├── data/                # Mock/API data
│   │   └── TshaPlayerData.ts
│   ├── pages/               # Routes
│   │   ├── Dashboard.tsx
│   │   ├── PlayerComparison.tsx
│   │   └── PlayerDetails.tsx
│   ├── types/               # Type definitions
│   │   └── Player.ts
│   ├── utils/               # Utilities
│   │   └── mIModels.ts
│   ├── App.tsx              # Root component
│   └── main.tsx             # Entry point
├── .gitignore
└── config.json              # App configuration
🚀 Quick Start
Clone & Install:
bash
git clone [your-repo-url]
cd nba-tracker
npm install
Run Dev Server:
bash
npm run dev
Build for Productions
bash
npm run build
📈 Roadmap
Integrate live NBA API (replace mock data
Add player shot charts visualization
Implement advanced filters (PER, TS%)
