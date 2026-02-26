# Defix-Finance

A DeFi support website where users can resolve wallet-related issues.

## Overview

Defix-Finance is a one-stop DeFi solution that helps users resolve cryptocurrency wallet issues. The website features a modern dark theme with teal/cyan accent colors, matching the reference designs provided.

## Project Structure

```
client/                    # Frontend React application
├── src/
│   ├── components/       # React components
│   │   ├── header.tsx           # Navigation header with logo
│   │   ├── hero-section.tsx     # Main landing hero section
│   │   ├── stats-section.tsx    # Market stats display
│   │   ├── products-section.tsx # Product tabs and features
│   │   ├── assets-section.tsx   # Supported assets section
│   │   ├── features-section.tsx # Feature cards
│   │   ├── services-section.tsx # Service categories grid
│   │   ├── wallet-modal.tsx     # Wallet selection modal
│   │   ├── connection-modal.tsx # Connection progress modal
│   │   └── footer.tsx           # Site footer
│   ├── pages/
│   │   └── home.tsx             # Main home page
│   └── index.css                # Tailwind CSS with dark theme
server/                    # Express backend
├── routes.ts             # API routes
└── storage.ts            # In-memory storage
shared/
└── schema.ts             # TypeScript types and schemas
```

## Key Features

1. **Landing Page** - Hero section with product showcase
2. **Service Categories** - 22 different wallet issue categories
3. **Wallet Connection** - Modal with popular wallet options
4. **Connection Flow** - Multi-step connection process with progress

## Design System

- **Theme**: Dark mode by default
- **Primary Color**: Teal/Cyan (HSL: 168 76% 42%)
- **Background**: Very dark gray (HSL: 0 0% 5%)
- **Font**: Inter for UI text

## API Endpoints

- `GET /api/services` - Get list of service categories
- `POST /api/submissions` - Submit wallet connection request
- `GET /api/stats` - Get market statistics

## Running the Project

The project runs on port 5000 with:
- Express backend serving API routes
- Vite development server for React frontend

## Recent Changes

- January 2026: Initial implementation with full frontend and backend
