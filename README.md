<!-- Banner + TL;DR Intro -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=120&section=header&text=CarbonTrackr&fontSize=40&fontColor=fff&animation=fadeIn" width="100%" alt="CarbonTrackr Wave Banner"/>

<div align="center">

## 🌱 CarbonTrackr - Your Personal Carbon Footprint Logger

> **TL;DR:**  
> Track, analyze, and reduce your carbon footprint with our sleek full-stack web app! Real-time data visualization, streak tracking, reduction targets, and personalized tips to help you become more eco-friendly.
>
> _Let's make the planet greener, one log at a time!_ 🌍

</div>

---

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/🌱-Carbon_Tracking-32CD32?style=for-the-badge&logo=leaf&logoColor=white" height="30" alt="Carbon Tracking Badge"/>
  <img src="https://img.shields.io/badge/⚡-Vite_Powered-646CFF?style=for-the-badge&logo=vite&logoColor=white" height="30" alt="Vite Badge"/>
  <img src="https://img.shields.io/badge/🚀-TypeScript_Backend-3178C6?style=for-the-badge&logo=typescript&logoColor=white" height="30" alt="TypeScript Badge"/>
  <img src="https://img.shields.io/badge/📊-Real_Time_Charts-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" height="30" alt="Charts Badge"/>
</p>

---

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=32CD32&center=true&vCenter=true&width=900&lines=🌍+Track+Your+Carbon+Footprint;📊+Visualize+Environmental+Impact;🎯+Set+%26+Achieve+Reduction+Goals;🏆+Build+Sustainable+Habits;⚡+Real-time+WebSocket+Updates;🔥+Full-stack+TypeScript+Power" alt="Typing Animation"/>

---

## 🎮 Featured Project Overview

**CarbonTrackr** is a modern, full-stack web application designed to help users track, analyze, and reduce their carbon footprint. Built with modern technologies and a focus on user experience and security, it makes environmental responsibility engaging and achievable.

---

## 🚀 Epic Features & Superpowers

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="300" alt="Features Animation"/>

```yaml
authentication: "🔐 Secure JWT-based login & registration"
activity_logging: "📝 Track daily carbon-producing activities"
data_visualization: "📊 Interactive Chart.js powered dashboards"
reduction_targets: "🎯 Set & track weekly/monthly reduction goals"
streak_tracking: "🔥 7-day activity streaks & achievements"
leaderboard: "🏆 Compete with others for lowest emissions"
real_time_tips: "💡 WebSocket-powered personalized suggestions"
weekly_summaries: "📈 Automated weekly analysis & insights"
category_filtering: "🔍 Filter by Transport, Food, Energy, etc."
responsive_design: "📱 Beautiful UI that works everywhere"
```

---

## 🖥️ Terminal Mode - Project Architecture

```bash
┌─[developer@carbontrackr]─[~/carbon-footprint-logger]
└──╼ $ tree -I node_modules
📁 carbon-footprint-logger/
├── 📁 client/                    # Frontend (Vite + Vanilla JS)
│   ├── 📄 API_DOCS.md            # Complete API documentation
│   ├── 📄 package.json           # Frontend dependencies
│   ├── 📄 index.html             # Main HTML template
│   ├── 📁 public/                # Static assets
│   └── 📁 src/                   # Source magic happens here
│       ├── 📄 main.js            # App entry point & initialization
│       ├── 📄 activity-data.js   # Emission factors database
│       ├── 📄 calculations.js    # CO₂ calculation engine
│       ├── 📄 api.js             # Axios instance & interceptors
│       ├── 📄 auth.js            # Authentication logic
│       ├── 📄 authEvents.js      # Auth form handlers
│       ├── 📄 logging.js         # CRUD operations & API calls
│       ├── 📄 ui.js              # DOM manipulation & rendering
│       ├── 📄 chart.js           # Chart.js integration
│       ├── 📄 filter.js          # Category filtering
│       ├── 📄 form.js            # SweetAlert2 modals
│       ├── 📄 socket.js          # WebSocket management
│       ├── 📄 targets.js         # Reduction targets logic
│       └── 📁 utils/             # Helper utilities
└── 📁 server/                    # Backend (Node.js + TypeScript)
    ├── 📄 package.json           # Backend dependencies
    ├── 📄 tsconfig.json          # TypeScript configuration
    ├── 📄 docker-compose.yml     # Docker setup
    ├── 📄 Dockerfile             # Container definition
    ├── 📁 public/                # API documentation site
    └── 📁 src/                   # Server-side powerhouse
        ├── 📄 server.ts          # Express app & socket setup
        ├── 📁 db/                # Database initialization
        ├── 📁 middleware/        # Auth middleware
        ├── 📁 models/            # MongoDB schemas
        ├── 📁 routes/            # API endpoint definitions
        ├── 📁 sockets/           # WebSocket event handlers
        ├── 📁 jobs/              # Scheduled weekly analysis
        └── 📁 utils/             # Server utilities

┌─[developer@carbontrackr]─[~/status]
└──╼ $ git status
 On branch main
 🔥 Status: Production ready & actively maintained
 📈 Features: Activity logging, targets, real-time tips
 🎯 Next: Advanced analytics, AI insights
```

---

## 🛠️ Tech Arsenal & Superpowers

### Frontend Magic ✨

![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-%23FF6384.svg?style=for-the-badge&logo=chartdotjs&logoColor=white)
![SweetAlert2](https://img.shields.io/badge/SweetAlert2-%23E91E63.svg?style=for-the-badge&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-%235A29E4.svg?style=for-the-badge&logo=axios&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

### Backend Power 🔧

![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-%23000000.svg?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-%23010101.svg?style=for-the-badge&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-%23000000.svg?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### DevOps & Tools 🚀

![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🚀 Quick Start - Get Running in Minutes!

### 🔧 Prerequisites

- **Node.js** (v18+ recommended) - The JavaScript runtime
- **npm or yarn** - Package manager of choice
- **MongoDB** - Database (or use Docker setup)
- **Docker** (optional) - For containerized deployment

### 📁 Cloning the Repository

**Important:** This project uses Git submodules for modular architecture!

```bash
# Clone with all submodules
git clone --recurse-submodules https://github.com/siyabuilds/carbon-footprint-logger.git

# Or if already cloned without submodules
git submodule update --init --recursive
```

### 🎨 Frontend Setup (Client)

```bash
cd client
npm install                    # Install dependencies
npm run dev                    # Start dev server
```

🌐 Open [http://localhost:5173](http://localhost:5173) - Frontend ready!

### 🏗️ Backend Setup (Server)

```bash
cd server
npm install                    # Install dependencies
npm run dev                    # Start development server
```

⚡ Backend running on [http://localhost:3000](http://localhost:3000)

### 🐳 Docker Deployment (One-Click Setup)

```bash
cd server
docker-compose up --build      # Magic happens here!
```

🎉 **Backend:** `localhost:4500` | **MongoDB:** `localhost:27017`

---

## 📊 App Features Deep Dive

### 🔐 Authentication System

- Secure JWT-based login/registration
- Email or username login support
- Auto-logout on token expiration
- Protected routes and API endpoints

### 📝 Activity Logging

- Track activities across 6+ categories (Transport, Food, Energy, etc.)
- Real-time CO₂ calculations
- Activity history with timestamps
- Bulk delete and management

### 🎯 Reduction Targets

- Set weekly/monthly reduction goals
- Percentage or absolute emission targets
- Progress tracking and visualization
- Target history and management

### 📈 Data Visualization

- Interactive Chart.js powered dashboards
- Category breakdowns and totals
- Progress charts and trends
- Real-time updates

### 🏆 Leaderboard & Social

- Compare with other users
- Lowest emission rankings
- Activity streak tracking
- Achievement system

### ⚡ Real-time Features

- WebSocket-powered live updates
- Personalized eco-tips after logging
- Real-time progress notifications
- Live activity feed

---

## 🔌 API Endpoints Quick Reference

| Method   | Endpoint                      | Description                 |
| -------- | ----------------------------- | --------------------------- |
| `POST`   | `/api/register`               | Create new user account     |
| `POST`   | `/api/login`                  | User authentication         |
| `GET`    | `/api/validate`               | Validate JWT token          |
| `GET`    | `/api/activities`             | Get user's activities       |
| `POST`   | `/api/activities`             | Log new activity            |
| `DELETE` | `/api/activities/:id`         | Delete specific activity    |
| `GET`    | `/api/activities/leaderboard` | Get rankings                |
| `GET`    | `/api/streaks`                | Get 7-day activity streak   |
| `GET`    | `/api/summaries/current`      | Current week summary        |
| `GET`    | `/api/targets`                | Get active reduction target |
| `POST`   | `/api/targets`                | Create reduction target     |
| `PUT`    | `/api/targets/:id`            | Update reduction target     |

📚 **Full Documentation:** See [`client/API_DOCS.md`](client/API_DOCS.md) for complete API reference!

---

## 🏆 Project Achievements

<div align="center">

| Achievement          | Status | Description                            |
| -------------------- | ------ | -------------------------------------- |
| **🌱 Eco-Friendly**  | ✅     | Carbon footprint tracking & reduction  |
| **⚡ Real-time**     | ✅     | WebSocket integration for live updates |
| **📊 Data Viz**      | ✅     | Interactive charts & analytics         |
| **🎯 Goal Setting**  | ✅     | Reduction targets & progress tracking  |
| **🏆 Gamification**  | ✅     | Streaks, leaderboards & achievements   |
| **🔐 Secure**        | ✅     | JWT authentication & protected routes  |
| **🐳 Containerized** | ✅     | Docker & docker-compose ready          |
| **📱 Responsive**    | ✅     | Mobile-friendly design                 |

</div>

---

## 🌍 Environmental Impact

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="300" alt="Environmental Impact"/>

### 📈 Success Metrics

- Activities logged and CO₂ calculated
- Reduction targets set and achieved
- User streaks and engagement
- Community leaderboard participation

---

## 🛠️ Development & Contributing

### 🔄 Development Workflow

1. **Fork** the repository
2. **Clone** your fork with submodules
3. **Create** a feature branch
4. **Develop** your amazing feature
5. **Test** thoroughly
6. **Submit** a pull request

### 🚀 Deployment

- **Frontend:** Deploy to Vercel/Netlify
- **Backend:** Deploy to Render/Heroku/DigitalOcean
- **Database:** MongoDB Atlas for production

---

## 📚 Learning Resources

### 🎯 Tech Stack Deep Dives

- [Vite Documentation](https://vitejs.dev/) - Lightning fast build tool
- [Chart.js Guide](https://www.chartjs.org/) - Beautiful data visualization
- [Express.js Tutorial](https://expressjs.com/) - Web framework for Node.js
- [Socket.io Docs](https://socket.io/) - Real-time communication
- [MongoDB University](https://university.mongodb.com/) - Database mastery

---

## 🌍 Let's Connect & Build a Greener Future Together!

<table>
<tr>
<td align="center">
<a href="https://github.com/siyabuilds/carbon-footprint-logger" target="_blank">
<img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white" height="40" alt="GitHub"/>
</a><br>
<sub><b>Source Code</b></sub>
</td>
<td align="center">
<a href="https://carbontrackr.vercel.app" target="_blank">
<img src="https://img.shields.io/badge/Live_Demo-%2300C7B7.svg?style=for-the-badge&logo=vercel&logoColor=white" height="40" alt="Live Demo"/>
</a><br>
<sub><b>Try CarbonTrackr</b></sub>
</td>
<td align="center">
<a href="mailto:siyabonga.lukhele@umuzi.org" target="_blank">
<img src="https://img.shields.io/badge/Contact-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" height="40" alt="Contact"/>
</a><br>
<sub><b>Get In Touch</b></sub>
</td>
<td align="center">
<a href="https://siyabuilds.tech" target="_blank">
<img src="https://img.shields.io/badge/Portfolio-%2347A3F3.svg?style=for-the-badge&logo=safari&logoColor=white" height="40" alt="Portfolio"/>
</a><br>
<sub><b>More Projects</b></sub>
</td>
</tr>
</table>

### 💬 Let's Collaborate On

- 🌱 **Environmental tech solutions**
- 🚀 **Full-stack development projects**
- 📊 **Data visualization innovations**

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=120&section=footer&text=Thanks%20for%20Going%20Green!&fontSize=35&fontColor=fff&animation=fadeIn" width="100%" alt="Footer Banner"/>

<div align="center">

**Made with 💚 for a sustainable future**

_"The best time to plant a tree was 20 years ago. The second best time is now."_ 🌳

</div>
