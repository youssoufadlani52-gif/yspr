# YSPR — Youssef Pictures

**Independent pictures · Product engineering · Motion experiments**

YSPR is the portfolio identity and source repository for Youssef Pictures. The visual direction combines 1930s rubber-hose illustration, 1980s anime title-card energy, and retro-futurist print design.

## Current repository state

This repository has been initialized. The full portfolio implementation and its research package are being transferred from the working source archive in a follow-up commit. Until that transfer and a successful CI build are complete, this README does not claim that the live site is production-ready.

## Intended stack

- React 19 + Vite
- GSAP + ScrollTrigger
- Lenis smooth scrolling
- Lucide React
- CSS-led art direction, responsive layouts, and reduced-motion support

## Planned experience

- Editorial hero and project index
- Filterable selected work with project case files
- Archive ledger
- About dossier and workshop notes
- Motion studies and an experimental film room
- Contact finale

## Local development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

## Research and implementation notes

The research directory will document visual references, motion studies, implementation decisions, tool evaluations, and validation status. Tool evaluations are not represented as executed unless their runtime output is recorded.

## Status

**In progress.** The repository should not be treated as complete until the source transfer, dependency installation, production build, and browser QA have all passed.
