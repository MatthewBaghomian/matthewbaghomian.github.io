# Website

> the website for the engineering 1 project.

The site is built with React, Vite, TypeScript and Tailwind CSS.

### Files Structure

```
yetti-web/
├── src/
│   ├── App.tsx <- The main component of the project, contains the main markup and logic of the site
│   ├── index.css <- Main CSS file of the project, including Tailwind CSS themes and custom fonts
│   ├── main.tsx <- The main entry point of Vite
│   └── ...
├── public/ <- The public folder, contains the static files of the project, such as the favicon or any images
├── .github/
│   ├── workflows/ <- The GitHub Actions workflows for the project
│   │   ├── static.yml <- The workflow for the static site deployment to GitHub Pages
│   └── ...
```

### Local Development

```bash
git clone https://github.com/yetti-eng/website.git
cd website
bun install
bun run dev
```

### Build

```bash
bun run build
```
