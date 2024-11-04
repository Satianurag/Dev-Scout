# Dev Scout

Dev Scout is a web application that allows developers to create and join coding rooms, collaborate on projects, and find like-minded individuals to work with.

## Features

- User authentication
- Create and manage coding rooms
- Browse and join existing rooms
- Real-time video chat in rooms
- Tagging system for easy room discovery
- GitHub repository integration

## Tech Stack

- Next.js 14 with App Router
- TypeScript
- React
- Tailwind CSS
- Shadcn UI
- Radix UI
- Drizzle ORM
- PostgreSQL
- NextAuth.js for authentication
- Stream for video chat functionality

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- PostgreSQL database

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Satianurag/Dev-Scout.git
   cd dev-finder
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:
   ```
   DATABASE_URL=your_postgresql_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   NEXT_PUBLIC_GET_STREAM_API_KEY=your_stream_api_key
   GET_STREAM_SECRET_KEY=your_stream_secret_key
   ```

4. Run database migrations:
   ```
   npm run db:migrate
   ```

5. Start the development server:
   ```
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

- `src/app`: Next.js app router pages and API routes
- `src/components`: Reusable React components
- `src/db`: Database schema and configuration
- `src/lib`: Utility functions and shared logic
- `src/data-access`: Data access layer for database operations
