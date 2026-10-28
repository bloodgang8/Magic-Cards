# Gift Card Platform

## Overview
A production-ready digital gift card platform for managing virtual gift cards, top-ups, user access, and audit logs.

## Stack
- React + Vite + Tailwind
- Express + Prisma
- PostgreSQL
- Stripe
- JWT authentication
- Docker
- GitHub Actions

## Features
- Gift card creation and management
- Card activation and redemption
- Balance top-ups
- Payment processing via Stripe Checkout
- User registration and login
- Admin role management
- Audit logging
- Password reset and email verification
- CSV export for transactions
- Deployment workflow documentation

## Admin login
- Email: admin@example.com
- Password: admin123

## Local setup

### Backend
```bash
cd backend
cp .env.example .env
npm install
npx prisma generate
npx prisma db push
npm run seed
npm run dev# Magic-Cards