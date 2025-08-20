# Petals - Gen Z Dating Application

A modern, privacy-focused dating platform designed specifically for Generation Z, built with cutting-edge technologies and a mobile-first approach.

## Technology Stack

### Mobile Application
- **Framework**: Expo React Native
- **UI Library**: Tamagui for consistent, performant design system
- **Authentication**: Clerk for secure, seamless user authentication
- **Data Fetching**: TanStack Query for efficient server-state management
- **State Management**: Zustand for lightweight client-side state
- **Database Client**: Supabase client for real-time data synchronization

### Backend Services
- **Framework**: Express.js with TypeScript
- **Authentication**: Clerk middleware integration
- **Database Operations**: Supabase Service Role for secure server-side data access
- **API Design**: RESTful architecture with real-time capabilities

### Database & Infrastructure
- **Primary Database**: Supabase (PostgreSQL)
- **Extensions**: 
  - Realtime for live updates and notifications
  - Storage for media file management
  - pgvector for AI-powered matching and recommendations
- **Authentication**: Integrated Clerk user management

## Project Structure

```
petals/
├── mobile/          # React Native mobile application
├── backend/         # Express.js API server
├── supabase/        # Database migrations and configurations
├── docs/            # Documentation and guides
└── infra/           # Infrastructure as code and deployment
```

## Getting Started

1. Clone the repository
2. Copy `.env.example` to `.env` and configure environment variables
3. Install dependencies in each package directory
4. Follow component-specific setup instructions

## Development

Each component directory contains its own `README.md` with detailed setup and development instructions. The monorepo is designed for independent development of each component while maintaining integration consistency.
