# Portfolio Template

A minimalist developer portfolio with blog functionality, built with Next.js 14, Tailwind CSS, and Framer Motion.

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animation**: Framer Motion
- **UI Components**: shadcn/ui (Radix UI primitives)
- **Content**: MDX for blog posts
- **Package Manager**: pnpm

## Project Structure

```
├── content/           # MDX blog content
├── public/            # Static assets (images, resume)
├── src/
│   ├── app/          # Next.js App Router pages
│   ├── components/   # React components
│   ├── data/         # Resume and portfolio data
│   └── lib/          # Utility functions
└── tailwind.config.ts
```

## Available Skills

| Skill | Description |
|-------|-------------|
| `build-and-deploy` | Build and deploy to Vercel or Netlify |

## Customization

1. Edit `src/data/resume.tsx` to update personal information
2. Add blog posts to `content/` directory as MDX files
3. Update images in `public/` directory

## Development

```bash
pnpm install
pnpm dev
```

## Deployment

Use the `build-and-deploy` skill to deploy to Vercel or Netlify.
