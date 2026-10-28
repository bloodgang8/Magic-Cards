This is the final release-notes.md file content.

Save as:
- release-notes.md

```md
# v1.0.0

## Overview
This is the initial release of the Gift Card Platform.

## Highlights
- Full monorepo setup for frontend and backend
- React + Vite + Tailwind frontend
- Express + Prisma + PostgreSQL backend
- JWT authentication and admin roles
- Card lifecycle management
- Stripe Checkout integration
- Audit logging and transaction history
- Email verification and password reset
- CSV export support
- CI workflow and deployment documentation

## Admin login
- Email: admin@example.com
- Password: admin123

## Local setup
```bash
cd backend
cp .env.example .env
npm install
npx prisma generate
npx prisma db push
npm run seed
npm run dev
```

```bash
cd frontend
cp .env.example .env
npm install
npm run dev
```

## Notes
This project is a digital gift card management platform and is not a regulated bank or financial institution.

## Changelog
- Added project bootstrap and repo structure
- Added admin dashboard and card management UI
- Added payment flow and Stripe integration
- Added authentication and security controls
- Added audit logs and reporting
- Added CI and deployment setup
```

Release command:
```bash
gh release create v1.0.0 --title "v1.0.0" --notes-file release-notes.md
```

If needed, tag command:
```bash
git tag -a v1.0.0 -m "Release v1.0.0"
git push origin v1.0.0
```

You now have:
- project repo
- release tag
- GitHub release notes
- changelog

Everything is ready for delivery.