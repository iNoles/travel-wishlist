# Travel Wishlist

A full-stack travel planning application to manage and track your dream destinations. Users can register, log in, create destinations, and mark them as visited. The app features secure authentication, JWT refresh tokens, and automated tests for both backend and frontend.

---

## Features

- User registration and login with JWT and refresh tokens
- Secure password validation (minimum 8 characters, uppercase, special character)
- CRUD for destinations: add, view, and mark as visited
- ASP.NET Core backend with Entity Framework Core
- Vue 3 frontend with reactive state management
- Unit tests (xUnit) for backend auth flows
- End-to-end tests (Playwright) for frontend auth and dashboard interactions

---

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
