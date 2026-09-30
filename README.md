This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### Project Structure

```
nextjs-v16-upstream/
├── app/
│   ├── favicon.ico          # App favicon
│   ├── globals.css          # Global styles with Tailwind
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Home page
├── public/                  # Static SVG assets
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   └── window.svg
├── .gitignore               # Git ignore file
├── cacheHandler.ts          # Legacy cache handler (ISR, route handlers, fetch)
├── eslint.config.mjs        # ESLint configuration
├── LICENSE                  # MIT License
├── next-env.d.ts            # Next.js TypeScript declarations
├── next.config.ts           # Next.js configuration with dual cache handlers
├── package.json             # Dependencies
├── postcss.config.mjs       # PostCSS configuration for Tailwind
├── README.md                # This file
├── tsconfig.json            # TypeScript configuration
└── use-cache-handler.ts     # Next.js 16 'use cache' directive handler
```

### Additional Resources

- [Next.js 16 Release Notes](https://nextjs.org/blog/next-16)
- [Pantheon Cache Handler](https://github.com/pantheon-systems/nextjs-cache-handler)
- [Turbopack Documentation](https://nextjs.org/docs/app/api-reference/turbopack)

### Support

For issues related to:
- **Next.js:** [Next.js GitHub](https://github.com/vercel/next.js)
- **Pantheon Cache Handler:** [pantheon-systems/nextjs-cache-handler](https://github.com/pantheon-systems/nextjs-cache-handler)
- **Pantheon Platform:** [Pantheon Documentation](https://docs.pantheon.io)
