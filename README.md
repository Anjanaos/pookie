# Anonymous Dating App

A simple anonymous dating web app built with Next.js, Tailwind CSS, and Prisma (SQLite).

## Features

- **Anonymous Profiles**: Users remain anonymous with no personal information required.
- **Interest-Based Matching**: Match with students who share common interests.
- **Reactions**: Like or pass on potential matches.
- **Mutual Matches**: Chat with users who have mutually liked each other.
- **Time Restrictions**: App is active only between 6 AM and 11 PM.
- **Safety Features**: Anonymous interactions to ensure privacy.
- **Pinkish Theme**: Minimal design with a pink color scheme.

## Tech Stack

- **Framework**: Next.js 16 with App Router
- **Styling**: Tailwind CSS
- **Database**: Prisma with SQLite
- **Language**: TypeScript

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up the database:
   ```bash
   npx prisma migrate dev --name init
   npx prisma generate
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. On first visit, select your interests.
2. Browse potential matches based on shared interests.
3. Like or pass on profiles.
4. View your mutual matches and start chatting.

## Project Structure

- `app/`: Next.js app directory with pages and components
- `lib/`: Utility functions and database client
- `prisma/`: Database schema and migrations

## Build

To build for production:
```bash
npm run build
```

## Deploy

Deploy to Vercel or any platform supporting Next.js.
