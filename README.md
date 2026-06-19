<div align="center">
  <img src="public/dev.png" width="128" height="128" alt="Portfolio Logo" />
  <h1>Portfolio Website</h1>

  <p><strong>showcasing developer, creator, gallery, skills and gamer perspectives.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status" />
    <img src="https://img.shields.io/badge/License-MIT-blue" alt="License" />
    <img src="https://img.shields.io/badge/Type-Portfolio-lightblue" alt="Type" />
  </p>
</div>

---

built with **React**, **TypeScript**, and **Tailwind CSS**. skills, interests, professional projects, and curated content from Spotify, YouTube, and Instagram. Features smooth animations, and a polished UI powered by shadcn-ui components.

## Screenshots

  <img src="https://i.postimg.cc/8cZwwNm8/Screenshot-2026-05-24-192358.png" alt="Hero Section" />


### Installation

```sh
# Step 1: Clone the repository
git clone https://github.com/Sahil-dev7/Portfolio

# Step 2: Navigate to project directory
cd sahilportfolio27; npm install

# Step 3: Start development server
npm run dev
```

The portfolio will be available at `http://localhost:5173` with hot module reloading enabled.

## Project Structure

```
src/
├── components/
│   ├── [Persona Pages] — Developer.tsx, Friend.tsx, Gamer.tsx
│   ├── [Sections] — Hero, Skills, Projects, Interests, etc.
│   ├── PersonaSwitcher.tsx — Persona selection component
│   ├── Scene3D.tsx — WebGL 3D rendering
│   ├── Navbar.tsx — Navigation header
│   ├── Footer.tsx — Footer with links
│   └── ui/ — shadcn-ui component library
├── pages/ — Main persona page views
├── hooks/
│   ├── use-mobile.tsx — Mobile device detection
│   └── use-toast.ts — Toast notifications
├── lib/ — Utility functions
├── test/ — Unit tests with Vitest
└── [Config files] — Vite, TypeScript, Tailwind configs
```


### Customization Guide

**Update Personal Information:**
- Edit persona content in `src/components/Developer.tsx`, `Friend.tsx`, `Gamer.tsx`
- Modify skill list in `src/components/SkillsSection.tsx`
- Update projects in `src/components/ProjectsSection.tsx`

**Styling:**
- Tailwind theme colors in `tailwind.config.ts`
- Global styles in `src/index.css`
- Component-specific styles in respective TSX files

**Add New Sections:**
1. Create component in `src/components/`
2. Import in respective persona page
3. Style with Tailwind CSS classes

**Social Links & Contact:**
- Update URLs in `src/components/Footer.tsx`
- Modify contact methods in `src/components/ContactSection.tsx`


## Tech Stack

<p align="center">
  <a href="https://sahilw.pages.dev">
    <img src="https://skillicons.dev/icons?i=react,vite,tailwind,github,html,css,threejs,linux,neovim,cloudflare" />
  </a>
</p>


## License

This portfolio is open source and licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.
