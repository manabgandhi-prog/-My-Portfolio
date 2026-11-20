# Manab Gandhi — 3D Developer Portfolio Website

A modern, responsive, 3D personal developer portfolio website designed for **Manab Gandhi**, 2nd-year B.Tech Computer Science & Engineering student and aspiring software developer.

Built with **React 18**, **TypeScript**, **Tailwind CSS**, **Three.js** (WebGL 3D interactive graphics), and **Lucide Icons**.

---

## ✨ Features & Highlights

1. **Interactive 3D WebGL Universe (Three.js)**:
   - Dynamic 3D cyber core with an animated wireframe icosahedron, orbital glowing torus rings, and 1,000+ interactive starry constellation particles reacting in real-time to mouse cursor position and parallax scrolling.
   - Interactive 3D Card Tilt on all project and focus cards with perspective rotations and realistic specular light glares.

2. **Authentic, Transparent Student Representation**:
   - Zero inflated 99% progress bars or fabricated work experience.
   - Highlights honest proficiency in **Python (Beginner)** and active study in **Data Structures & Algorithms**, **Problem Solving**, and **Software Engineering Fundamentals**.
   - Accurately positions conceptual projects (Smart Attendance System, AI Smart Learning Platform, Landslide Warning System) with technical architectural blueprints.

3. **Complete Section Structure**:
   - **Hero**: Personalized introduction, animated typing roles (*"Aspiring Software Developer"*, *"Python Learner"*, *"Future Engineer"*), interactive terminal preview card (`student_env.py`), CTAs, and social links.
   - **About Me**: Natural personal narrative and 4 quick-glance 3D info cards.
   - **Skills**: Clean competency matrix categorized into Core Programming, Currently Learning, and Foundations.
   - **Projects**: 3D tilt project cards featuring custom artwork, status indicators (*"In Progress"*, *"Idea / Concept"*), tech tags, and a modal for exploring technical architecture.
   - **Education**: Modern vertical timeline with coursework highlights (2nd-Year B.Tech CSE, West Bengal, India, 2023–2027).
   - **Currently Learning Dashboard**: Real-time study tracker breaking down weekly learning sprints, DSA progress, and resources.
   - **Activities & Hackathons**: Verified student activities and hackathon ideation engagements.
   - **Contact**: Validated contact form, one-click email copy button with toast feedback, and celebration confetti animation.
   - **Dark / Light Mode**: Smooth theme toggling with persistent local storage.

4. **1-Minute Customization (`src/data/portfolioData.ts`)**:
   - All profile data, project details, college name, graduation year, social links, and email are centralized in `src/data/portfolioData.ts`.

---

## 🚀 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Local Development Server
```bash
npm run dev
```
The site will be live at `http://localhost:3000`.

### 3. Build for Production
```bash
npm run build
```
Production assets are generated in the `dist/` directory, optimized with code splitting for Three.js, React, and UI vendors.

---

## 🌐 Deploy to Vercel or Netlify

### Deploying to Vercel
1. Push this repository to GitHub.
2. Sign in to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Framework Preset will automatically detect **Vite**.
5. Click **"Deploy"**!

### Deploying to Netlify
1. Connect your repository on [Netlify](https://app.netlify.com).
2. Set Build command: `npm run build`
3. Set Publish directory: `dist`
4. Click **"Deploy site"**!

---

## 🛠️ Tech Stack

- **Framework**: Vite + React 18
- **Language**: TypeScript
- **3D Graphics**: Three.js (WebGL)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Animations**: CSS Transforms & Canvas Confetti

---

Designed & Built with ❤️ for Manab Gandhi.
*"Always learning. Always building."*
