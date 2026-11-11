# Kindora

> Give something you no longer need to someone who needs it. No money involved.

Kindora is a community platform for giving away items for free. Givers post
items, people nearby request them through private in-app messages, and the two
arrange collection themselves. There are no prices, payments, or shipping.

Every listing gets its own randomly generated public name, so visitors can't
tell which listings come from the same person.

## Status

🚧 Early development: Phase 0 (project foundation).

## Tech stack

- **Frontend:** React, Vite, Tailwind CSS, React Router, TanStack Query,
  React Hook Form, Zod
- **Backend:** Node.js, Express, MongoDB with Mongoose, JWT authentication
- **Language:** JavaScript (ES modules)

## Repository layout

This is a monorepo (one repository holding several related projects):

| Folder            | What it contains                                     |
| ----------------- | ---------------------------------------------------- |
| `apps/web`        | React single-page application (coming in Phase 0)    |
| `apps/api`        | Express REST API (coming in Phase 0)                 |
| `packages/shared` | Validation schemas and constants used by both apps   |

## Prerequisites

- Node.js 24 LTS (see `.nvmrc`)
- Git

Setup instructions will be added as the project grows.

## Security

Never commit `.env` files or credentials. Only `.env.example` files with
placeholder values belong in the repository.
