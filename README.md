# Real-Time Cryptocurrency Price Tracking

A modern, high-performance web application for real-time cryptocurrency price tracking, built with Next.js 15 and React 19. This project demonstrates advanced frontend development practices, including real-time data visualization, responsive design, and optimal performance.

## ✨ Features

### Core Features

- Real-time cryptocurrency price tracking with WebSocket integration
- Interactive price chart using D3.js for advanced data visualization
- Responsive design optimized for all device sizes
- Real-time price updates with smooth animations

### Technical Features

- **Performance Optimization**

  - Server-side rendering (SSR) with Next.js

- **SEO & Accessibility**

  - Comprehensive meta tags and OpenGraph support
  - Dynamic sitemap generation

- **Testing & Quality Assurance**

  - Unit tests with Vitest
  - Component testing with user interactions
  - Test coverage reporting

- **Developer Experience**

  - TypeScript for type safety
  - ESLint and Prettier for code consistency
  - Husky for pre-commit hooks
  - Conventional commits with commitlint

## 🛠️ Tech Stack

- **Framework**: Next.js 15.3.3 with React 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **Data Visualization**: D3.js 7.9.0
- **Animations**: React Spring 10.0.1
- **Package Manager**: pnpm
- **Testing**: Vitest with React Testing Library
- **Code Quality**:
  - ESLint with TypeScript support
  - Prettier for code formatting
  - Husky for git hooks
  - Commitlint for conventional commits

## 🏗️ Project Structure

```
src/
├── app/                    # Next.js app router pages and layouts
│   ├── favicon.ico        # Application favicon
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout component
│   ├── page.tsx           # Home page component
│   └── sitemap.ts         # Dynamic sitemap generation
│
├── components/            # Shared UI components
│   └── json-ld.tsx       # JSON-LD structured data component
│
├── core/                 # Core application logic
│   ├── types/           # TypeScript type definitions
│   └── utils/           # Utility functions and helpers
│
├── features/            # Feature-based modules
│   └── home/           # Home page feature module
│       ├── components/ # Feature-specific components
│       ├── hooks/     # Custom hooks
│       └── utils/     # Feature-specific utilities
│
└── test/               # Test configuration and utilities
    ├── setup/         # Test setup files
    └── utils/         # Test utilities and helpers
```

Each directory serves a specific purpose:

- **app/**: Contains Next.js app router pages and layouts, including the root layout and global styles
- **components/**: Houses reusable UI components used across the application
- **core/**: Contains core application logic, types, and utility functions
- **features/**: Implements feature-based modules following domain-driven design principles
- **test/**: Contains test configuration, setup files, and testing utilities

## 🚀 Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- pnpm (Latest version)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Vytautas/BTC-tracking
   cd BTC-tracking
   ```

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Start the development server:
   ```bash
   pnpm dev
   ```

The application will be available at `http://localhost:3000`.

## 🧪 Testing

Run the test suite:

```bash
# Run tests
pnpm test

# Run tests in watch mode
pnpm test:watch

# Generate test coverage
pnpm test:coverage
```

## 📝 Code Quality

- **Linting**: `pnpm lint`
- **Formatting**: `pnpm format`
- **Format Check**: `pnpm format:check`

## 🏗️ Build

Create a production build:

```bash
pnpm build
```

Start the production server:

```bash
pnpm start
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

[Vytautas](https://github.com/VytautasAI)

---

Built by Vytautas using Next.js and React
