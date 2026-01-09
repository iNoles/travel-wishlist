# Travel Wishlist - Full-Stack Web Application

Travel Wishlist is a full‑stack web application that lets users plan and track dream travel destinations. It demonstrates real‑world software development skills, including secure authentication, backend APIs, database integration, frontend UI, and automated testing.

## Project Overview

This app allows users to:

- Register and log in with secure authentication
- Create, view, and mark destinations as visited
- Interact with a frontend that consumes a RESTful API
- Persist data using a backend database
- Use automated tests to validate functionality

This project simulates the development workflow used in professional environments.

## Tech Stack

**Backend**
- ASP.NET Core Web API
- Entity Framework Core
- SQLite database
- JWT authentication with refresh tokens

**Frontend**

- Vue 3
- TypeScript
- Reactive state management

**Testing**

- Backend: xUnit unit tests
- Frontend: Playwright end‑to‑end tests

**Tools**

- Git / GitHub for version control
- Bun / npm for package management
- Docker (optional deployment enhancements

## Features

- User registration and login with JWT and refresh tokens
- Secure password validation (minimum 8 characters, uppercase, special character)
- CRUD for destinations: add, view, and mark as visited
- ASP.NET Core backend with Entity Framework Core
- Vue 3 frontend with reactive state management
- Unit tests (xUnit) for backend auth flows
- End-to-end tests (Playwright) for frontend auth and dashboard interactions

## Setup

### Backend

1. Clone the repo:  
   ```bash
   git clone https://github.com/iNoles/travel-wishlist.git
   cd backend
   ```
2. Configure ```appsettings.json``` with your JWT secret and database settings.
3. Run migrations:
   ```bash
   dotnet ef database update
   ```
4. Run the backend:
   ```bash
   dotnet run
   ```
### Frontend

1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies using Bun
   ```bash
   bun install
   ```
3. Run the dev server:
   ```bash
   bun dev
   ```

## Testing

### Backend
Run xUnit tests:
```bash
dotnet test backend.Tests
```

### Frontend
Run Playwright tests:
```bash
npx playwright test
```

## What This Demonstrates (for Employers)

This project showcases your ability to:

✔️ Build a secure full‑stack web application from scratch  
✔️ Implement **authentication and authorization**  
✔️ Design and integrate a backend REST API  
✔️ Build a **responsive user interface** that talks to the backend  
✔️ Write **automated tests** showing professional development skills  
✔️ Organize a project resembling a real job task
