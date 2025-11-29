N E B U L Δ ™ - Discord Bot Dashboard

A modern, animated dashboard website for the N E B U L Δ ™ Discord bot built with React, Vite, and GSAP.

## Features

- **Dark Futuristic Theme** - Pure black background with white text
- **Smooth Animations** - GSAP-powered transitions and scroll effects
- **Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- **Multiple Pages** - Home, Features, Commands, Support, and Invite sections
- **Glass Morphism UI** - Modern glassmorphic design patterns
- **Starfield Background** - Animated celestial background

## Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Custom CSS
- **Animations**: GSAP
- **UI Components**: Shadcn UI + Lucide Icons
- **Routing**: Wouter
- # N E B U L Δ ™ - Discord Bot Dashboard

A modern, animated dashboard website for the N E B U L Δ ™ Discord bot built with React, Vite, and GSAP.

## Features

- **Dark Futuristic Theme** - Pure black background with white text
- **Smooth Animations** - GSAP-powered transitions and scroll effects
- **Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- **Multiple Pages** - Home, Features, Commands, Support, and Invite sections
- **Glass Morphism UI** - Modern glassmorphic design patterns
- **Starfield Background** - Animated celestial background

## Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Custom CSS
- **Animations**: GSAP
- **UI Components**: Shadcn UI + Lucide Icons
- **Routing**: Wouter

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev:client

# Build for production
npm run build
```

## Deployment


### Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project" and import your repository
4. Vercel will auto-detect the Vite configuration
5. Click "Deploy"

The `vercel.json` file is pre-configured for optimal settings.

# N E B U L Δ ™ - Discord Bot Dashboard

A modern, animated dashboard website for the N E B U L Δ ™ Discord bot built with React, Vite, and GSAP.

## Features

- **Dark Futuristic Theme** - Pure black background with white text
- **Smooth Animations** - GSAP-powered transitions and scroll effects
- **Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- **Multiple Pages** - Home, Features, Commands, Support, and Invite sections
- **Glass Morphism UI** - Modern glassmorphic design patterns
- **Starfield Background** - Animated celestial background

## Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Custom CSS
- **Animations**: GSAP
- **UI Components**: Shadcn UI + Lucide Icons
- **Routing**: Wouter

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev:client

# Build for production
npm run build
```

## Deployment

### Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project" and import your repository
4. Vercel will auto-detect the Vite configuration
5. Click "Deploy"

The `vercel.json` file is pre-configured for optimal settings.

### Netlify

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git" and select your repository
4. Build command: `npm run build`
5. Publish directory: `dist/public`
6. Click "Deploy"

The `netlify.toml` file is pre-configured with redirects for SPA routing.

### Build Output

The production build is generated in the `dist/public` directory and is ready to be deployed to any static hosting service.

```bash
npm run build
# Output will be in dist/public/
```

## Project Structure

```
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   └── layout/
│   │   │       ├── Navbar.tsx
│   │   │       └── StarBackground.tsx
│   │   ├── pages/
│   │   │   ├── Home.tsx
│   │   │   ├── Features.tsx
│   │   │   ├── Commands.tsx
│   │   │   ├── Support.tsx
│   │   │   └── Invite.tsx
│   │   ├── App.tsx
│   │   └── index.css
│   └── index.html
├── vercel.json
├── netlify.toml
└── package.json
```

## Environment Variables

No environment variables are required for basic deployment. The bot invite and support links are hardcoded.

## Customization

### Change Bot Invite Link
Update the Discord OAuth URL in:
- `client/src/pages/Home.tsx`
- `client/src/components/layout/Navbar.tsx`
- `client/src/pages/Invite.tsx`

Replace `client_id=1434857888081248287` with your bot's client ID.

### Change Support Server
Update the support server link in:
- `client/src/pages/Home.tsx`
- `client/src/components/layout/Navbar.tsx`
- `client/src/pages/Support.tsx`

Replace `https://dc.gg/nebula-support` with your server invite link.

### Customize Theme
Edit `client/src/index.css` to modify:
- Colors and gradients
- Font families
- Animation timings
- Spacing and sizing

## Performance Optimizations

- Vite provides fast HMR (Hot Module Replacement)
- Tree-shaking removes unused code
- Automatic code splitting for optimal load times
- Asset optimization during build

## Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers

## License

MIT License - feel free to use this template for your own projects.

## Support

For issues or questions, visit the [Support Server](https://dc.gg/nebula-support)
