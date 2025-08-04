# Notion-Warp

A modern Next.js application bootstrapped with comprehensive development tooling.

## Features

- **Next.js 15** with App Router and TypeScript
- **TailwindCSS 4** for styling
- **ESLint** for code quality
- **Prettier** for code formatting
- **Husky + lint-staged** for pre-commit hooks
- **Commitlint** for conventional commits
- **Storybook** with Vite for UI component development
- **Absolute imports** with `@` alias
- **Vitest** for testing

## Getting Started

First, install dependencies:

```bash
pnpm install
```

Then, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Development Scripts

- `pnpm dev` - Start the development server
- `pnpm build` - Build the application for production
- `pnpm start` - Start the production server
- `pnpm lint` - Run ESLint
- `pnpm lint:fix` - Run ESLint with auto-fix
- `pnpm format` - Format code with Prettier
- `pnpm format:check` - Check code formatting
- `pnpm storybook` - Start Storybook development server
- `pnpm build-storybook` - Build Storybook for production

## Storybook

This project includes Storybook for component development and documentation:

```bash
pnpm storybook
```

Open [http://localhost:6006](http://localhost:6006) to view the component library.

## Project Structure

```
├── src/
│   ├── app/          # Next.js app directory
│   └── stories/      # Storybook stories
├── .storybook/       # Storybook configuration
├── .husky/           # Git hooks
└── public/           # Static assets
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
