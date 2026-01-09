# Fintech Dashboard

A high-end financial dashboard built with Next.js 14, React, and Tailwind CSS.

## Features

- Dark theme with custom background (#09090b)
- Sidebar navigation with multiple menu items
- Financial Overview header
- Placeholder area for spending chart visualization
- Responsive layout
- Modern UI/UX design

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. Run the development server:
```bash
npm run dev
# or
yarn dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the dashboard.

## Project Structure

```
├── src/
│   ├── app/
│   │   ├── globals.css      # Global styles with Tailwind
│   │   ├── layout.tsx       # Root layout component
│   │   └── page.tsx         # Main dashboard page
│   └── components/
│       └── Sidebar.tsx      # Sidebar navigation component
├── package.json
├── tailwind.config.ts       # Tailwind CSS configuration
└── tsconfig.json            # TypeScript configuration
```

## Tech Stack

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library

## Customization

The dashboard uses a dark theme with the background color `#09090b`. You can customize colors in `tailwind.config.ts` and components in the `src/` directory.
