# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a React learning project focused on mastering React hooks (useState, useEffect, useContext), creating reusable components, building scalable applications with best practices, and learning real-time communication with Socket.IO and data fetching with Axios.

## Development Commands
- `pnpm dev` - Start development server with HMR
- `pnpm build` - Build for production
- `pnpm lint` - Run ESLint checks
- `pnpm preview` - Preview production build

## Tech Stack
- React 19 + Vite
- Tailwind CSS v4 (with @tailwindcss/vite plugin)
- ESLint with React hooks and refresh plugins
- pnpm as package manager
- Socket.IO for real-time communication
- Axios for HTTP requests

## Code Architecture
- `/src/components/` - Reusable React components
- `/src/App.jsx` - Main application component
- `/src/main.jsx` - Application entry point

## ESLint Configuration
- Custom rules for unused variables with pattern matching (`^[A-Z_]`)
- React hooks validation enabled
- Component refresh validation for HMR

## Language Preferences
- Responde en español pero puedes usar terminologias en ingles (ejemplo, useEffect, node modules, prettier config, etc.)

## Learning Roadmap
- Se va a aprender sockets con socket io, y fetchData con axios