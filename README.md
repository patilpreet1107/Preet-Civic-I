# CivicTrack AI – Smart Civic Issue Reporting & Tracking System

CivicTrack AI is an AI-powered civic issue reporting web application designed to help citizens report and track urban infrastructure problems. It connects citizens with municipal authorities through a simple, interactive, and user-friendly platform.

Citizens can report problems such as potholes, damaged roads, overflowing garbage, broken streetlights, and drainage issues by uploading photographs and selecting their location on an interactive map.

The system uses AI-assisted analysis to suggest issue categories and priorities while keeping final decisions under human control.

## Key Features

### 1. Smart Issue Reporting
- Upload photographs of civic problems.
- Add issue descriptions.
- Select issue categories.
- Mark exact issue locations.

### 2. AI-Powered Issue Detection
- Uses local AI models through Ollama.
- Analyzes uploaded images.
- Suggests issue categories.
- Provides AI-based priority recommendations.
- AI suggestions require human verification.

### 3. Interactive Map
- OpenStreetMap integration.
- GPS-based location selection.
- Draggable map markers.
- Search locations using Nominatim.
- Category-based issue markers.

### 4. Issue Tracking
- Track reported civic issues.
- View issue details.
- Monitor issue status.
- Status flow: Reported → Under Review → In Progress → Resolved.

### 5. Citizen Rewards
- Earn points for reporting issues.
- Unlock achievement badges.
- Progress through different levels.
- View citizen leaderboard.

### 6. User-Friendly Dashboard
- Modern responsive interface.
- Dark-themed dashboard.
- Issue statistics.
- Mobile-friendly navigation.
- Smooth animations.

## Technology Stack

**Frontend**
- React.js
- Vite
- Tailwind CSS
- React Router DOM
- Framer Motion
- Lucide React

**Maps & Location**
- Leaflet
- React Leaflet
- OpenStreetMap
- Nominatim API

**Artificial Intelligence**
- Ollama
- Gemma 3 (Vision Model)
- Llama 3 (Text Model)

**Authentication & Storage**
- Firebase Authentication (Optional)
- Browser LocalStorage

**Testing**
- Vitest
- React Testing Library

## AI Models Setup

Install Ollama and download the required models:

```bash
ollama pull gemma3:4b
ollama pull llama3
```

Start Ollama locally:

```bash
ollama serve
```

## Installation & Run

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project folder:

```bash
cd CivicTrack-AI
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Run tests:

```bash
npm test
```

## Project Objectives

- Make civic issue reporting easier for citizens.
- Improve communication between citizens and authorities.
- Use AI to assist in identifying infrastructure problems.
- Encourage citizens to participate in city improvement.
- Provide transparent issue tracking.

## Privacy & Security

- AI processing is designed to use local Ollama models.
- Personal information is not intentionally shared with external AI models.
- AI recommendations are advisory only.
- Citizen reports are stored locally in the browser unless additional backend services are configured.

## Limitations

- The current MVP uses browser LocalStorage.
- No production municipal database is connected.
- AI predictions may not always be accurate.
- Issue resolution statuses may be demonstration-only.
- Production deployment requires proper backend infrastructure and municipal integration.

## Future Enhancements

- Municipal authority admin dashboard.
- Real-time notifications.
- Cloud database integration.
- Advanced AI issue detection.
- Multilingual support.
- Public issue analytics.

## Project Status

🚧 Currently under development.

**CivicTrack AI – Report Issues. Track Progress. Build Better Cities.**
