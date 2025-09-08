# Carbon Footprint Logger

Carbon Footprint Logger is a modern web application designed to help users track, analyze, and reduce their carbon footprint. The project features a full-stack architecture with a Vite-powered frontend and a TypeScript/Node.js backend, making it easy to log activities, visualize data, and monitor progress toward a more sustainable lifestyle.

## Features
- **User Authentication**: Secure login and registration.
- **Activity Logging**: Record daily activities that impact your carbon footprint.
- **Data Visualization**: Interactive charts and analytics to track your progress.
- **Streaks & Achievements**: Stay motivated with streak tracking.
- **RESTful API**: Well-documented endpoints for all core features.

## Project Structure
```
carbon-footprint-logger/
├── client/   # Frontend (Vite, JS)
├── server/   # Backend (Node.js, TypeScript)
```

## Cloning the Repository
**Important:** This project uses Git submodules for the frontend and backend. To clone the repository with all submodules, use:

```sh
git clone --recurse-submodules https://github.com/siyabuilds/carbon-footprint-logger.git
```

If you already cloned without `--recurse-submodules`, run:

```sh
git submodule update --init --recursive
```

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Docker (optional, for containerized backend)

### Frontend (Client)

1. Navigate to the client directory:
   ```sh
   cd client
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn
   ```
3. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Backend (Server)

1. Navigate to the server directory:
   ```sh
   cd server
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn
   ```
3. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```
4. The backend will run on [http://localhost:3000](http://localhost:3000) by default.

#### Using Docker (Optional)
You can run the backend with Docker:
```sh
cd server
docker-compose up --build
```

## API Documentation
See `client/API_DOCS.md` for details on available endpoints and usage examples.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features.

## License
This project is licensed under the MIT License.