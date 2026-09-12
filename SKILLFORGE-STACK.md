# SkillForge AI — Verified Technology Stack

This file is based on the uploaded `SkillForge-AI-v2-integrated.zip`.

## Programming languages / source languages
- TypeScript
- JavaScript
- HTML
- CSS

## Frontend
- React 18
- Vite
- React Router
- Tailwind CSS

## Backend
- Node.js
- Express.js
- CORS
- dotenv

## AI
- Groq API
- OpenAI-compatible chat-completions interface
- Configurable Groq model (the project currently defaults to `openai/gpt-oss-120b`)

## 3D / animation
- Three.js
- React Three Fiber
- @react-three/drei
- Framer Motion

## Documents
- PDF.js (`pdfjs-dist`)
- jsPDF

## Tooling
- npm
- TypeScript compiler
- PostCSS
- Autoprefixer
- Git / GitHub
- GitHub Actions

## Important accuracy note
The project README contains an outdated sentence referring to Anthropic, but the actual
server implementation sends requests to Groq's API. The profile therefore lists Groq,
not Anthropic, as the project's AI API.

## No database claim
The supplied project does not contain a database dependency or database server
implementation in `package.json`, so no database is listed as part of the verified stack.
