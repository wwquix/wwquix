# Yuri — Backend Developer in Progress

I am building a practical backend engineering portfolio around **Python**, **Node.js**, APIs, databases, testing, deployment, and automation.

My current goal is to become ready for **Backend Trainee / Junior**, **QA Automation**, **API Integration**, or **Reporting Automation** roles. I use AI tools to accelerate development, but I focus on understanding the architecture, testing behavior, reading logs, and being able to explain and change the code myself.

## Target roles

- Python Backend Trainee / Junior Developer
- Node.js Backend Trainee / Junior Developer
- QA Automation Trainee with Python
- API / Integration Support Engineer
- Junior Data or Reporting Automation Specialist

## Current backend stack

### Languages and runtimes

- Python 3
- JavaScript
- Node.js

### Backend and APIs

- Express 5
- REST APIs and JSON contracts
- Twitch Helix API and EventSub WebSocket
- OAuth 2.0 authorization flow
- Server-Sent Events
- Telegram Bot API
- Input validation with Zod

### Data

- SQLite
- SQL fundamentals
- Database schemas, relations, transactions, backups, and exports
- CSV and XLSX data export

### Testing and code quality

- pytest fundamentals
- Vitest
- Supertest
- ESLint
- Integration tests with temporary databases
- GitHub Actions CI

### Deployment and operations

- Linux VPS
- SSH
- Nginx
- systemd
- Environment variables and secret management
- Application logs and basic production diagnostics
- Git and GitHub

## Featured projects

### [Fenya Stream Lab](https://github.com/wwquix/fenya-stream-lab)

A full-stack Twitch analytics application with a substantial Node.js backend.

**Backend highlights:**

- Node.js and Express 5 API
- React dashboard with normalized API contracts
- Twitch OAuth login and channel roles
- Twitch Helix HTTP integration
- EventSub WebSocket chat ingestion
- Server-Sent Events replay mode
- SQLite persistence with WAL mode and foreign keys
- Layered routes, services, providers, repositories, and storage modules
- Zod validation for JSON and CSV imports
- Database-backed sessions with hashed opaque tokens
- AES-256-GCM encryption for stored Twitch tokens
- Role-based route middleware
- Integration tests with Vitest and Supertest
- GitHub Actions checks for test, lint, and build
- Deployment on a Linux VPS behind Nginx

**What this project demonstrates:** API integration, authentication, real-time events, database design, backend layering, security boundaries, testing, and deployment.

### [KBJU Tracker Bot](https://github.com/wwquix/kbju-tracker-bot)

A Python Telegram bot for nutrition, body-weight, and workout tracking.

**Backend highlights:**

- Python application split into bot, database, and service modules
- SQLite schema for users, daily logs, workouts, exercises, and sets
- Deterministic free-text nutrition and workout parsers
- User-isolated Telegram commands
- Double-progression workout recommendations
- Safe SQLite online backups
- CSV and XLSX exports
- Application logging
- Environment-based secrets and user allowlists
- Database and parser test scripts

**What this project demonstrates:** Python application structure, data modeling, parsing, reporting, backups, and defensive handling of user input.

### [Morning Brief](https://github.com/wwquix/morning-brief)

A Python automation project that generates a daily personal briefing and delivers it through Telegram and Windows notifications.

**Highlights:**

- Multiple external API integrations
- Markdown and self-contained HTML generation
- React and Vite frontend embedded into generated reports
- Telegram document delivery
- Environment-based secret handling
- Windows Task Scheduler and Linux cron deployment options
- Linux VPS setup documentation

**What this project demonstrates:** automation, API consumption, scheduled jobs, report generation, and cross-platform deployment.

## Current learning roadmap

### 1. Production-style FastAPI service

Build a backend project with:

- FastAPI
- PostgreSQL
- SQLAlchemy 2
- Alembic migrations
- Pydantic validation
- Session or JWT authentication
- Role-based authorization
- Pagination, filtering, and search
- pytest integration tests
- Dockerfile and Docker Compose
- Health and readiness endpoints
- Structured logging
- OpenAPI documentation
- GitHub Actions CI

The project should solve a real problem rather than only demonstrate CRUD operations.

### 2. Containerized Node.js backend

Upgrade Fenya Stream Lab with:

- Dockerfile and Docker Compose
- PostgreSQL instead of SQLite for the production profile
- Database migrations
- Container health checks
- Repeatable local setup with one command
- Separate development and production configuration
- Reverse-proxy deployment documentation

### 3. Backend reliability skills

Deepen practical knowledge of:

- HTTP status codes and error contracts
- Transactions and database indexes
- Authentication and authorization boundaries
- Rate limiting
- Idempotency
- Background jobs
- Redis fundamentals
- CI/CD
- Monitoring and structured logs
- Debugging unfamiliar code

## What I am working on now

- Strengthening independent Python fundamentals through CS50P-style exercises
- Learning SQL and PostgreSQL
- Rewriting and extending project features without relying on complete AI-generated solutions
- Adding tests before making larger architecture changes
- Preparing for trainee-level technical interviews and small test assignments

## Development principles

- Understand the code before presenting it as a skill
- Prefer one well-tested project over many unfinished demos
- Keep secrets outside the repository
- Document setup, architecture, limitations, and trade-offs
- Use AI as an assistant for explanation, review, and iteration—not as a substitute for understanding
- Build projects that can be run, tested, and reviewed by another developer

## Contact

- GitHub: [@wwquix](https://github.com/wwquix)
