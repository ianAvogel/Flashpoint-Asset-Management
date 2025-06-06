# FlashPoint Asset Management

This repository contains a small static web interface for managing asset inspections. A simple Node.js server is provided to serve the pages so the application can be started easily.

## Structure

```
public/
  index.html
  dashboard.html
  upload.html
  asset.html
server.js
```

## Running locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Open your browser to <http://localhost:3000>

The Express server will serve the static files from the `public` directory and route `/dashboard`, `/upload`, and `/asset` to their respective pages.
