# Sweedan Cardoza - Portfolio Website

A modern, responsive portfolio website showcasing AI/ML projects and skills. Built with Next.js, TypeScript, Tailwind CSS, and shadcn/ui.

## Features

- **Modern Hero Section** - Animated text effects with blur animations
- **About Section** - Education and career goals
- **Skills Section** - Interactive skill bars with proficiency levels
- **Projects Portfolio** - Showcase of SwiftNotes, Finance Tracker, and PortWise
- **Contact Section** - Contact form and social links
- **Dark Mode** - Theme toggle functionality
- **Responsive Design** - Mobile-first approach with breakpoints

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Icons:** Lucide React
- **Shaders:** @paper-design/shaders-react

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
portfolio-website/
├── app/
│   ├── demo/
│   │   ├── hero/          # Demo page for hero component
│   │   └── shader/         # Demo page for shader component
│   ├── layout.tsx          # Root layout with fonts
│   ├── page.tsx            # Main portfolio page
│   └── globals.css         # Global styles
├── components/
│   ├── sections/           # Page sections
│   │   ├── about-section.tsx
│   │   ├── skills-section.tsx
│   │   ├── projects-section.tsx
│   │   └── contact-section.tsx
│   └── ui/                 # UI components
│       ├── portfolio-hero.tsx
│       └── portfolio-hero-with-paper-shaders.tsx
└── lib/
    └── utils.ts            # Utility functions
```

## Components

### Portfolio Hero (`components/ui/portfolio-hero.tsx`)
- Animated hero section with blur text effects
- Navigation menu
- Theme toggle
- Scroll indicator

### Portfolio Hero with Shaders (`components/ui/portfolio-hero-with-paper-shaders.tsx`)
- Resume/CV layout with shader effects
- Split-screen design
- Theme toggle

### Sections
- **About Section:** Education and background information
- **Skills Section:** Technical skills with proficiency indicators
- **Projects Section:** Project cards with details
- **Contact Section:** Contact form and social links

## Customization

### Updating Personal Information

1. **Hero Section:** Edit `components/ui/portfolio-hero.tsx`
   - Change name from "SWEEDAN CARDOZA" to your name
   - Update profile image URL
   - Modify tagline

2. **About Section:** Edit `components/sections/about-section.tsx`
   - Update education details
   - Modify career goals text

3. **Skills:** Edit `components/sections/skills-section.tsx`
   - Update skills array with your skills and proficiency levels

4. **Projects:** Edit `components/sections/projects-section.tsx`
   - Update projects array with your project details
   - Add GitHub and demo URLs

5. **Contact:** Edit `components/sections/contact-section.tsx`
   - Update email, GitHub, and LinkedIn links
   - Configure form submission endpoint

### Styling

- **Colors:** The accent color `#C3E41D` is used throughout. Search and replace to change.
- **Fonts:** Fira Code and Antic are loaded via Next.js font optimization in `app/layout.tsx`
- **Theme:** Dark/light mode is handled via Tailwind's dark mode

## Demo Pages

- `/demo/hero` - Hero component demo
- `/demo/shader` - Shader component demo

## Build for Production

```bash
npm run build
npm start
```

## Deployment

The site can be deployed on:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **AWS Amplify**
- Any platform supporting Next.js

## License

This project is private and personal.

## Contact

Sweedan Cardoza
- Email: sweedan.cardoza@example.com
- GitHub: github.com/sweedancardoza
- LinkedIn: linkedin.com/in/sweedancardoza
