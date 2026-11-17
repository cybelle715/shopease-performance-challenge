# ShopEase – React + Tailwind Performance Challenge

## Project overview
ShopEase is a small online-store interface provided for the SWE203 Week 6 practical activity. The application is intentionally imperfect. Your task is to inspect it, identify performance and functionality problems, improve the code, and submit your work through a GitHub Pull Request.

## Requirements
- Node.js (LTS version recommended)
- npm
- Git
- Google Chrome
- A GitHub account

## Run the project locally

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal (usually `http://localhost:5173`).

## Practical tasks

### 1. Git workflow
1. Clone the repository.
2. Create a branch named `feature/performance-optimization`.
3. Do not commit directly to `main`.

### 2. Inspect the application
Use Chrome Developer Tools:
- **Console:** identify JavaScript errors.
- **Network:** inspect image and JavaScript file sizes and loading times.
- **Performance:** record the page and investigate long tasks.
- **Lighthouse:** run a Mobile audit and record the Performance score and available metrics.

Record at least three issues before making changes.

### 3. Improve the application
Apply appropriate fixes. Consider image loading, image dimensions, JavaScript execution, bundle size and unnecessary code. Do not change the visual design more than necessary.

### 4. Compare results
Run Lighthouse again using the same device category and comparable conditions. Record the before-and-after results. Do not invent measurements.

### 5. Submit your work

```bash
git add .
git commit -m "Improve ShopEase performance"
git push -u origin feature/performance-optimization
```

Open a Pull Request on GitHub targeting `main` (or the target branch specified by your lecturer). Include:
- Problems identified
- Changes made
- Before-and-after Lighthouse results
- Any remaining limitations

## Important
This is a learning exercise. The code contains intentional issues. Do not assume every warning reported by Lighthouse is caused by your code; investigate each finding before changing anything.
