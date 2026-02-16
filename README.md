# 2025-BOILERPLATE-ASTRO

## ES NECESARIO DESVINCULAR EL GIT DEL CUAL SE CLONA Y AGREGAR A UN NUEVO REPOSITORIO EL NUEVO PROYECTO
### npm install
### npm run dev

## AHORA DESVINCULAR

### git remote -v => para ver repositiorios vinculados
### git remote remove origin (para desvincularlo)

### git remote -v => Ya no debería de aparecer ningún valor en fetch y push
### agrega a tu nuevo repositorio 


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   ├── fonts/
│   ├── images/
│   └── favicon.svg
├── src
│   ├── assets/
│   │   ├── fonts/
│   │   └── images/
│   │
│   ├── components/
│   │   └── BaseHead.astro
│   │
│   ├── constants/
│   │
│   ├── hooks/
│   │
│   ├── layouts/
│   │   └── Layout.astro
│   │
│   ├── lib/
│   │
│   ├── pages/
│   │    └── index.astro
│   │
│   ├── styles/
│   │   ├── partials/
│   │   │   ├── _colors.css
│   │   │   ├── _containers.css
│   │   │   ├── _fonts.css
│   │   │   ├── _tags.css
│   │   └── global.css
│   │
│   ├── types/
│   │
│   ├── utils/
│   │   └── siteTheme.ts
│   │
│   └── notes.txt
├── package.json
├── astro.config.mjs
└── tsconfig.json
```

## 🚀 Dependencies

```text
Review package.json for the latest dependency versions.
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
