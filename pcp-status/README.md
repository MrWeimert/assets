# PCP status feed

Machine-written status for the Project Control Panel dashboard.

- `status.json` — updated by scheduled tasks:
  - **Daily commit check** (7:00 AM CT): refreshes `repos[]` from GitHub
  - **Mon/Thu keepalive** (8:00 AM CT): refreshes `supabase[]` after pinging each Supabase project

The PCP wireframe at [mohawk-projects.pplx.app](https://mohawk-projects.pplx.app) fetches this file on page load via `raw.githubusercontent.com`.

Last verified: 2026-07-27
