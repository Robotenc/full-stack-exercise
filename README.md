# Leaderboard API - Take-Home Exercise

**Time limit:** 3-4 hours max

## The Challenge

Build a basic leaderboard API for a gaming platform.

## Requirements

**Tech Stack:** NestJS + PostgreSQL + TypeORM

**API Endpoints:**

- `POST /scores` - Submit a score (user_id, score, timestamp)
- `GET /leaderboard` - Get top 10 players globally (by best score)
- `GET /leaderboard/user/:userId` - Get a user's rank and nearby players (5 above + user + 5 below)

**Additional Requirements:**

- Basic authentication (JWT or API key, your choice)
- Database schema design with appropriate indexes
- README with setup instructions
- Clean commit history showing your implementation progression
- Basic React UI (Vite or Next.js) that uses at least one of the API endpoints

## What We're Looking For

- Code quality, organization, formatting, and separation of concerns
- Database design decisions (how you handle rankings, ties, indexes)
- API design (validation, error handling, proper status codes)
- Clean UI/UX
- Clear documentation

## Submission Instructions

1. Clone this repository (do NOT fork)
2. Create a **private** repository on your GitHub account
3. Push your solution there
4. Add `@admin-robotenc` as a collaborator
5. Email the repo link to careers@robotenc.com

**Deadline:** 6 days from receipt

**Questions?** Email careers@robotenc.com - we're happy to clarify requirements.

---

_If you run out of time, submit what you have and note in your README what you would have added._
