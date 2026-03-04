# Bitasmbl-MicroSaaS-Subscriptions-Hub-614cdf-9b15c1dd694d

## Description
Build a small SaaS app where users sign up, manage a single feature-limited service, and view usage and billing-style summaries using a Python backend and Vue.js frontend.

## Tech Stack
- Vue.js
- Python

## Requirements
- Implement a Python HTTP API that supports CRUD-style operations for subscriptions and returns JSON responses.
- Create a Vue.js SPA that authenticates a mock user, manages subscriptions via forms, and displays real-time usage/billing summaries.

## Installation
bash
git clone https://github.com/MrBitasmblTester/Bitasmbl-MicroSaaS-Subscriptions-Hub-614cdf-9b15c1dd694d.git
cd Bitasmbl-MicroSaaS-Subscriptions-Hub-614cdf-9b15c1dd694d


## Usage
- Run Python HTTP API
- Run Vue.js dev server
- Open SPA in browser

## Implementation Steps
1. Set up Python HTTP API project structure.
2. Implement subscription CRUD endpoints returning JSON.
3. Create Vue.js SPA with mock authentication flow.
4. Add forms to create, update, and delete subscriptions via API.
5. Implement real-time usage and billing-style summary views.

## API Endpoints
- POST /subscriptions
- GET /subscriptions
- GET /subscriptions/{id}
- PUT /subscriptions/{id}
- DELETE /subscriptions/{id}