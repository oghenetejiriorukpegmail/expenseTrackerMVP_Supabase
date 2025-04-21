# Expense Tracker (Netlify Deployment)

This repository contains the expense tracker application configured for deployment on Netlify.

## Project Structure

- `client/`: Frontend React application
- `netlify/functions-src/`: Source code for Netlify Functions
- `netlify/functions/`: Compiled Netlify Functions
- `shared/`: Shared code between frontend and backend

## Deployment Configuration

- `netlify.toml`: Netlify deployment configuration
- `tsconfig.netlify.json`: TypeScript configuration for Netlify Functions

## Development

1. Install dependencies:
   ```
   npm install
   ```

2. Run the development server:
   ```
   npm run dev
   ```

3. Build for production:
   ```
   npm run build