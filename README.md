
![TailwindCSS-SoundMate-WebPage](https://github.com/user-attachments/assets/d4e0bba5-cf10-42f1-a795-cb70aab7c509) ![Screenshot 2024-08-25 at 04 38 07](https://github.com/user-attachments/assets/5f21efcb-2dfe-45b3-9643-f1b0478383d3)

## TailwindCSS-SoundMate-WebPage

TailwindCSS-SoundMate-WebPage is a demo single webpage with header logo, navbar, body with info, button, cards, footer and responsive screen for any device where using only TailwindCSS, Tailwind class extension JS and HTML.

## How to run this project

Open the index.html script, right-click on your mouse cursor on the index.html script then select the "Open with Live Server" option then it will automatically redirect to the browser as http://127.0.0.1:5500/index.html


## To Create TailwindCSS React Vite Project

Open up your terminal and bootstrap a new React Vite App by: `npm create vite@latest my-project -- --template react`

Then go to that project folder, and write this command via terminal from your project folder: `npm install -D tailwindcss postcss autoprefixer`

Then install tailwindcss and its peer dependencies, then generate your `tailwind.config.js` and `postcss.config.js` files: `npx tailwindcss init -p`

Then add the paths to all your template files in your tailwind.config.js file.

```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Then add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Run your project: `npm run dev`

Run on your browser Local: `http://localhost:5173/`

(For more details, visit: https://tailwindcss.com/docs/guides/vite )
