# Bajaj Qualifier APIs

This project implements the required REST APIs for the Bajaj / Chitkara University Qualifier (Feb 2026).

The application is built using **Node.js and Express** and exposes two public APIs as per the problem statement.

---

## Tech Stack

- Node.js
- Express.js
- Axios
- External AI API (Google Gemini – with graceful fallback)

---

## API Endpoints

### 1️⃣ Health Check API

**GET** `/health`

#### Response

```json
{
  "is_success": true,
  "official_email": "upnit4821.be23@chitkara.edu.in"
}
```
