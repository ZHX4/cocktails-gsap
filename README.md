# Cocktails GSAP

A modern, animated cocktail bar landing page built with React, GSAP, and Tailwind CSS. Features smooth scroll-triggered animations, text reveals, and parallax effects.

## Live Demo

[View Live Site](https://cocktails-gsap.vercel.app)

## Features

- Scroll-triggered animations using GSAP ScrollTrigger
- Text split animations with SplitText plugin
- Parallax effects on decorative elements
- Responsive design for mobile and desktop
- Custom fonts with optimized loading (no FOUT)
- Smooth scrolling navigation

## Tech Stack

- React 19
- Vite 7
- GSAP 3 (with ScrollTrigger, SplitText)
- Tailwind CSS 4
- react-responsive

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/ZHX4/cocktails-gsap.git

# Navigate to project directory
cd cocktails-gsap

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
  components/
    Navbar.jsx    - Fixed navigation bar
    Hero.jsx      - Landing section with parallax
    Cocktails.jsx - Cocktail showcase section
    About.jsx     - About section
    Art.jsx       - Art/gallery section
    Menu.jsx      - Menu display
    Contact.jsx   - Contact info and socials
  App.jsx         - Main app component
  index.css       - Global styles and Tailwind config
constants/
  index.js        - Site content and data
public/
  fonts/          - Custom fonts
  images/         - Static images
```

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## License

MIT
