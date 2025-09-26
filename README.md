# InvestPro - Ready-to-deploy (improved)

## Setup (local)

1. Copy `.env.example` to `.env` and set values.
2. `npm install`
3. `npm run seed` (creates DB, seeds products, creates admin from .env)
4. `npm start`
5. Open `http://localhost:3000/` (user) and `http://localhost:3000/admin` (admin backoffice)

## Notes
- Replace the payment skeleton with real provider integrations and webhook verification.
- Use HTTPS and strong secrets in production.
- Consider switching to PostgreSQL for production and add migrations.
