# Vite + Preact + Tailwind CSS

Install Vite

```
npm create vite@latest vite-preact-tailwind-seed --template preact-ts
cd vite-preact-tailwind-seed
npm install
npm run dev
```

Install Tailwind CSS

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

In tailwind.config.cjs, add the following:

```
content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```

In src/index.css, add the following (remove vite boilerplate):

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Finally run

```
npm run dev
```

Initialise git repository

```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/kkarad/vite-preact-tailwind-seed.git
git push -set-upstream origin master
```
