# English Lessons — Adeline Rocha Dornelles

Site de aulas particulares de inglês criado com **React, Vite, Tailwind CSS, Framer Motion e Zod**.

## Personalizar foto e textos

1. **Foto da professora:** salve uma foto na pasta `public/` (por exemplo `public/foto.jpg`) e em `src/config/site.ts` altere `photoUrl: ""` para `photoUrl: "/foto.jpg"`.
2. **Textos de formação, experiência, certificações e metodologia:** edite `src/config/site.ts`.

## Como colocar o site na internet (gratuito, sem precisar rodar build no PC)

1. Crie uma conta gratuita no **GitHub** e envie esta pasta para um repositório.
2. Crie uma conta gratuita na **Vercel** (<https://vercel.com>) ou **Netlify** (<https://www.netlify.com>) conectada ao seu GitHub.
3. Importe o repositório — a plataforma detectará **Vite** automaticamente (`npm run build` -> pasta `dist`) e publicará o site com link HTTPS gratuito.

## Rodar localmente (opcional)

Requer **Node.js** instalado (<https://nodejs.org>):

```bash
npm install
npm run dev
```
