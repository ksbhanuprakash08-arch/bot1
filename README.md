# Cloud Storage App

A simple client + server example that demonstrates file upload and storage using Supabase.

## Project structure

- `server.js` — Node.js server used by the project.
- `script.js` — Client-side JavaScript used in `index.html`.
- `index.html` — Main HTML UI for the demo.
- `files.html` — File listing UI.
- `test-storage.html`, `test-supabase.html` — Test pages.
- `create_dummy_users.js` — Helper to create dummy users (if needed).
- `SETUP_GUIDE.md`, `SUPABASE_SETUP.md`, `SUPABASE_DASHBOARD_SETUP.md` — Setup notes.

## Prerequisites

- Node.js (16+ recommended)
- A Supabase project with Storage enabled

## Setup

1. Install dependencies:

```bash
npm install
```

2. Configure environment variables (or update `server.js` with your keys):

- `SUPABASE_URL` — your Supabase project URL
- `SUPABASE_ANON_KEY` — your Supabase anon/public key

See `SUPABASE_SETUP.md` for more details about creating a Supabase project and obtaining keys.

## Run

Start the Node server (if the project uses it):

```bash
node server.js
```

Then open `index.html` in your browser to use the demo, or open the test pages:

- `test-storage.html` — test storage uploads/downloads
- `test-supabase.html` — Supabase connection tests

## Utilities

- Use `create_dummy_users.js` to create example users (requires valid Supabase keys).
- `update-files.js` (in `temp/`) and other helper scripts are for local testing.

## Troubleshooting

- Ensure your Supabase keys are correct and storage is enabled.
- Check browser console and server logs for error details.

## Notes

This repository contains basic demo code and setup notes. Refer to the `SUPABASE_*` markdown files for step-by-step Supabase instructions.

---

If you'd like a more detailed README (examples, API docs, or screenshots), tell me what to include and I'll extend it.