# Ecommerce Website React App

This is a React application for an ecommerce website with the following pages:
- Registration
- Login
- Catalogue
- Kart
- Contact
- About

## Features
- React Router for navigation between pages
- Simple forms for registration, login, and contact
- Sample product catalogue and kart display

## Setup and Run

1. Install dependencies:
```
npm install
```

2. Run the development server:
```
npm start
```

## Deployment to GitHub Pages

1. Replace `<your-github-username>` in the `homepage` field of `package.json` with your GitHub username.

2. Initialize a git repository if not already done:
```
git init
git remote add origin https://github.com/<your-github-username>/ecommerce-website.git
```

3. Commit your code:
```
git add .
git commit -m "Initial commit"
```

4. Push to GitHub:
```
git push -u origin main
```

5. Deploy to GitHub Pages:
```
npm run deploy
```

Your site will be available at:
```
https://<your-github-username>.github.io/ecommerce-website
```

## Notes
- Make sure you have the `gh-pages` package installed (already included in devDependencies).
- The `deploy` script builds the app and pushes the build folder to the `gh-pages` branch.
