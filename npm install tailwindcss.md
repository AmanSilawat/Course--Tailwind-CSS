npm init -y
npm install tailwindcss
<!-- npm install tailwindcss postcss-cli autoprefixer
npx tailwind init -->


Add in css
src/style.css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

Add in package.json
    "build-css": "tailwindcss build src/style.css -o public/style.css"

run in terminal
    npm run build-css

after some html and css work....

add config file (first code run in terminal)
    npx tailwindcss  init --full

