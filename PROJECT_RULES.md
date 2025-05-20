# Project Rules & Guidelines

This project implements a Conference Management System. Below is a condensed version of the rules to guide development.

## Tech Stack
- **Frontend**: React (Vite), React Router, Context API, Tailwind CSS, Axios
- **Backend**: Node.js, Express, PostgreSQL via Prisma, JWT auth, Zod/Joi validation

## Folder Layout
```
/backend - Express server
/frontend - React application
```
Detailed subfolders follow conventional structure (controllers, routes, components, pages, etc.).

## Git Workflow
- Use feature branches (e.g., `feature/<name>`)
- Commit messages: `[TYPE] Short description`
- Types: `feat`, `fix`, `chore`, `docs`, `refactor`, `test`, `style`

## Coding Standards
- Files and folders: kebab-case
- Variables/functions: camelCase
- Components/classes: PascalCase

## API Design
- RESTful endpoints under `/api/v1/...`
- Responses:
```json
{ "success": true, "message": "...", "data": {} }
```
- Errors:
```json
{ "success": false, "error": "...", "details": [] }
```

For full details see the project documentation.
