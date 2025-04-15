# Dan Agency Website

A sophisticated tech-forward website for Dan, a web design and development agency, built with Next.js, Tailwind CSS, Framer Motion, and Three.js.

## Project Overview

This project is a modern, dark-themed agency website that features:

- Sophisticated tech-forward aesthetic
- High-quality animations and interactive elements
- Responsive design for all devices
- Performance-optimized animations and effects

## Tech Stack

- **Framework**: Next.js with App Router
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion, GSAP
- **3D Graphics**: Three.js with React Three Fiber
- **Typography**: Inter (body) and Space Grotesk (headings)
- **Development**: TypeScript

## Features

### Design System

- Dark theme with electric blue, teal, and purple accents
- Custom Tailwind components and utility classes
- Responsive typography and spacing system

### Animations

- Particle network background effect
- Scroll-triggered animations
- Interactive hover effects
- Smooth page transitions
- Micro-interactions on UI elements

### Pages

- **Home**: Hero section with particle animation, services, work examples, testimonials, and contact form
- **About**: Company philosophy, team members, and values
- **Services**: Detailed service offerings
- **Work**: Portfolio grid with filterable categories and case studies
- **Process**: Step-by-step workflow visualization
- **Contact**: Contact form with animations

## Visual Identity

The visual identity follows a sophisticated tech-forward aesthetic with:

- Deep charcoal/navy backgrounds (#0A0F1A)
- Electric blue primary accent (#00A4FF)
- Vibrant teal secondary accent (#00F5C8)
- Vibrant purple accent (#9747FF)
- Clean typography with modern sans-serif fonts

## Getting Started

### Prerequisites

- Node.js 18.17 or later

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/dan-agency.git
cd dan-agency
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Build for Production

```bash
npm run build
npm run start
```

## Project Structure

```
dan/
├── src/
│   ├── app/                    # Next.js App Router
│   │   ├── about/              # About page
│   │   ├── services/           # Services page
│   │   ├── work/               # Work/Portfolio page
│   │   ├── process/            # Process page
│   │   ├── contact/            # Contact page
│   │   ├── page.tsx            # Homepage
│   │   ├── layout.tsx          # Root layout
│   │   └── globals.css         # Global styles
│   │
│   ├── components/
│   │   ├── layout/             # Layout components (Navbar, Footer)
│   │   ├── ui/                 # Reusable UI components
│   │   ├── animations/         # Animation components
│   │   └── sections/           # Page sections
│   │
│   └── lib/
│       └── utils.ts            # Utility functions
│
├── public/                     # Static assets
├── tailwind.config.js          # Tailwind configuration
└── README.md                   # Project documentation
```

## Design Notes

- The site follows a modular design approach with reusable components
- Animations are performance-optimized and enhance the user experience
- Dark theme provides a sophisticated, premium feel
- Interactive elements create engagement and highlight the agency's technical capabilities

## Animations

The website features several types of animations:

1. **Entrance Animations**: Elements fade in and slide up as they enter the viewport
2. **Interactive Animations**: Hover effects on buttons, links, and cards
3. **Background Animations**: Particle network in the hero section
4. **Micro-interactions**: Form field focus states, button hover/active states
5. **Transitions**: Smooth transitions between pages and sections

## Performance Considerations

- Animations are optimized for performance using Framer Motion's best practices
- Images are optimized and properly sized
- Components are lazy-loaded where appropriate
- Tailwind's JIT compiler ensures minimal CSS output

## Credits

- Design and Development: [Your Name]
- Animations: Framer Motion, GSAP, Three.js
- Typography: Inter and Space Grotesk fonts
