# RansomGuard Frontend

React web client for the Ransomware Detection and File Protection System. It uses Vite and communicates with the Spring Boot REST API.

## Run locally

1. Install Node.js.
2. Run `npm ci`.
3. Copy `.env.example` to `.env.local` and set `VITE_API_URL` to the backend API base URL (for local development, `http://localhost:8080/api`).
4. Run `npm run dev`.

`VITE_DEMO_ADMIN_EMAIL` and `VITE_DEMO_ADMIN_PASSWORD` are optional. If set in a client build, they appear publicly on the login page, so use only credentials intended for public demonstration.

## Checks

- `npm run lint`
- `npm run build`

The app provides login, file-check and prevention-task pages, and administrator views. The backend performs the actual file checks and database operations.