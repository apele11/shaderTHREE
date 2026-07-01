# ShaderTHREE - Shaders Crash Course

<img width="599" height="678" alt="image" src="https://github.com/user-attachments/assets/62a4d04e-4cc1-42eb-9f1c-581cf3e1a877" />


This project is a WebGL shader project built using Three.js and Webpack.

## Getting Started

Because the project configuration files are located inside the `shaders-crash-course-main` folder, you must navigate into that folder before running any commands.

### 1. Install Dependencies
Open your terminal and run:
```bash
cd shaders-crash-course-main
npm install
```

### 2. Run Development Server
To start the local development server:
```bash
cd shaders-crash-course-main
npm start
```
*Note: The project uses `npm start` (not `npm run dev`). Once started, open [http://localhost:8080](http://localhost:8080) in your browser.*

---

## Deployment

The project is configured to be deployed to GitHub Pages using the `gh-pages` package.

### 1. Build the Production Files
To generate the optimized build in the `dist` folder:
```bash
cd shaders-crash-course-main
npm run build
```

### 2. Deploy to GitHub Pages
To deploy the built `dist` folder to your GitHub Pages branch:
```bash
cd shaders-crash-course-main
npx gh-pages -d dist
```
*(This will push the contents of the `dist` folder to the `gh-pages` branch of your repository.)*
