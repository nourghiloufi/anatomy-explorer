# Anatomy Explorer

A bilingual (English/French) anatomy-learning app built with React, TypeScript, Vite, Three.js and React Three Fiber.

## Features

- Three switchable learning modes: 3D exploration, guided lessons, and fictional medical mysteries.
- Four difficulty levels: Beginner, Intermediate, Advanced and Expert.
- English/French language toggle.
- Interactive 3D anatomy scene with orbit controls, zoom and selectable organs.
- Organ profiles with functions, body-system labels and discovery facts.
- Guided cardiovascular lesson with a knowledge check.
- Fictional respiratory-system case study with answer feedback.
- XP, completed lesson tracking and progress persisted in browser local storage.
- Responsive desktop and mobile layout.

## Run locally

Requires Node.js 20 or newer.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Notes on educational content

The 3D body is a stylized learning visualization, not a clinically accurate anatomical model. The case studies are fictional and are not diagnostic tools or medical advice. Content is an introductory foundation and should be checked against trusted anatomy references before use in formal education.
