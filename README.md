# GREAT MONEY — Full Platform Starter

## Included
- Node.js + Express backend
- SQLite database
- Secure password hashing
- JWT login sessions
- Registration
- User dashboard
- ₦1,500 first-deposit payment flow
- Paystack initialization/verification hooks
- Admin login/API overview
- Responsive frontend

## Run locally
1. Install Node.js 18+.
2. Copy `.env.example` to `.env`.
3. Set a strong `JWT_SECRET`.
4. Set `ADMIN_EMAIL` and a strong `ADMIN_PASSWORD`.
5. Add your Paystack secret key as `PAYSTACK_SECRET_KEY`.
6. Set `PUBLIC_URL` to the URL where this app is hosted.
7. Run `npm install`.
8. Run `npm start`.
9. Open `http://localhost:3000`.

## Production requirements
Before accepting real customer money, configure HTTPS, a production database, backups, proper Paystack webhook/signature validation, admin controls, audit logs, privacy policy, terms, fraud controls, and any Nigerian legal/regulatory requirements applicable to the business.

This starter does not promise investment returns or guaranteed earnings. It is an online registration/account-management system with a first-deposit activation flow.
