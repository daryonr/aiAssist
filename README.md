# AI Phone Assistant

An intelligent phone assistant powered by AI that helps manage calls, messages, and more.

## Project Structure

```
ai-phone-assistant/
├── backend/         # Node.js/Express backend
├── frontend/        # Next.js frontend
└── docker-compose.yml
```

## Prerequisites

- Node.js (v18 or later)
- Docker and Docker Compose
- PostgreSQL (if running locally)

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ai-phone-assistant
   ```

2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   - Create `.env` files in both `backend/` and `frontend/` directories
   - Copy the contents from `.env.example` files (if available)

4. Start the development environment:
   ```bash
   docker-compose up
   ```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001
- Database: localhost:5432

## Development

- Frontend: Built with Next.js 14, React 18, and TailwindCSS
- Backend: Node.js with Express, TypeScript, and Prisma ORM
- Database: PostgreSQL

## License

[Add your license here] 