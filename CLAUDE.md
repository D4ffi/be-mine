# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# Objective
Crear un crucigrama atractivo para la vista y responsivo 

## Project Overview

Crucigrama is a crossword puzzle application built with React 19, TypeScript, and Vite 7.

## Development Commands

```bash
npm run dev      # Start development server with HMR
npm run build    # Type-check with tsc and build for production
npm run lint     # Run ESLint
npm run preview  # Preview production build locally
```

## Tech Stack

- **Framework**: React 19 with TypeScript
- **Build Tool**: Vite 7 with @vitejs/plugin-react
- **Linting**: ESLint 9 with typescript-eslint, react-hooks, and react-refresh plugins

## Architecture

- Entry point: `src/main.tsx` renders `<App />` inside `<StrictMode>`
- Static assets in `public/` are served at root path
- Assets in `src/assets/` are processed by Vite's asset pipeline
