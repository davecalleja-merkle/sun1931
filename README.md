# sun1931

asdasd

## Features

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS with design tokens
- **Components**: ShadCN UI components
- **Design Tokens**: Style Dictionary integration
- **Documentation**: Not included

## Getting Started

```bash
npm install
npm run setup
npm run dev
```

## Setup Instructions

- Run `npm run setup` to install registry items
- Run `npm run dev` to start development server
- Run `npm run build:tokens` to generate design tokens
- Design tokens will be available in the `dist` directory
- Run `npm run setup` to install selected components
- Components will be installed using ShadCN CLI

## Project Structure

```
├── app/                 # Next.js app directory
├── components/          # React components
├── lib/                 # Utility functions
├── tokens/              # Design tokens
├── dist/                # Generated design token outputs
└── scripts/             # Build and setup scripts
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run setup` - Install registry items
- `npm run build:tokens` - Build design tokens
- `npm run lint` - Run ESLint
