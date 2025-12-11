# THE MET Landing Page

This is a responsive landing page for The MET Museum, built using HTML, SCSS, and JavaScript.
The design is based on [Figma prototype](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET).

GitHub Pages:
https://dashasssss.github.io/layout-landing-page/

 Project Structure

layout-landing-page/
│
├── src/
│   ├── images/        # All images and icons
│   ├── scripts/       # JS logic (main.js, menu toggle, etc.)
│   ├── styles/        # SCSS styles, partials, variables
│   └── index.html     # Main HTML template
│
├── dist/              # Production build (auto-generated)
├── vite.config.js     # Vite configuration
├── package.json
├── .prettierrc
├── .gitignore
└── README.md

🛠 Technologies Used

* Vite — fast build tool for modern front-end
* HTML5 - Semantic markup
* SCSS — structured and modular styles
* JavaScript — basic interactivity (menu, scroll, etc.)
* Prettier — code formatting
* ESLint — code quality


📦 Installation & Running Locally

Clone the repository:
git clone https://github.com/dashasssss/layout-landing-page.git
cd layout-landing-page

Install dependencies:
npm install

Run development server:
npm run dev

Build production version:
npm run build

Preview production build:
npm run preview

✨ Features
* Fully responsive layout (mobile → tablet → desktop)
* Clean and maintainable SCSS architecture
* Smooth image scaling in "Now on View" section
* Accessible typography and semantic HTML
* Header burger menu with overlay navigation
* Optimized images for fast loading