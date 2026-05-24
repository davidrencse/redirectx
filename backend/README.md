# RedirectX Backend

Node.js, Express, and TypeScript REST API for RedirectX.

## Commands

```bash
npm install
npm run dev
npm run build
npm start
```

The API listens on `PORT` or `4000` by default. Storage is in-memory for the MVP as requested by the project plan, so scan records reset when the process restarts.

## Core endpoints

- `GET /api/health`
- `POST /api/scans`
- `GET /api/scans/:scanId`
- `GET /api/scans/:scanId/progress`
- `GET /api/scans/:scanId/endpoints`
- `GET /api/scans/:scanId/chains`
- `GET /api/scans/:scanId/findings`
- `GET /api/scans/:scanId/findings/:findingId`
- `GET /api/scans/:scanId/report?format=json`
- `GET /api/scans/:scanId/report?format=html`
- `POST /api/scans/:scanId/cancel`
- `GET /api/demo/datasets`
