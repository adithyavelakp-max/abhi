# GitHub Upload Instructions

## Files to Upload to GitHub

This folder contains all the files you need to upload to your GitHub repository: `abhishek-work`

## What's Included:

### 📁 Configuration Files (Root Level)
- `package.json` - Dependencies and scripts
- `vite.config.ts` - Build configuration with GitHub Pages settings
- `tsconfig.json` - TypeScript configuration
- `tsconfig.app.json` - TypeScript app configuration
- `tsconfig.node.json` - TypeScript node configuration
- `tailwind.config.ts` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
- `eslint.config.js` - ESLint configuration
- `components.json` - Shadcn UI configuration
- `index.html` - Main HTML file
- `README.md` - Project documentation
- `.gitignore` - Git ignore rules

### 📁 Source Code
- `src/` folder - All React components and application code
- `public/` folder - Static assets (favicon, images, etc.)

### 📁 GitHub Actions
- `.github/workflows/deploy.yml` - Automatic deployment workflow

## How to Upload to GitHub:

### Method 1: GitHub Web Interface (Easiest)
1. Go to: https://github.com/adithyavelakp-max/abhishek-work
2. Click "uploading an existing file" or drag and drop
3. Upload all files and folders from this `github-upload` folder
4. Commit the files

### Method 2: GitHub Desktop
1. Open GitHub Desktop
2. Clone your repository
3. Copy all files from this folder to the cloned repository folder
4. Commit and push

## After Upload:

### Enable GitHub Pages:
1. Go to repository Settings → Pages
2. Source: "GitHub Actions"
3. Save

### Your app will be live at:
https://adithyavelakp-max.github.io/abhishek-work/

## Important Notes:

- Make sure to upload the `.github` folder (it might be hidden)
- Keep the folder structure exactly as it is
- The `vite.config.ts` is already configured for your repository name
- GitHub Actions will automatically deploy when you push code

## File Count:
- Main files: 12
- Source files: 65
- Public files: 3
- GitHub workflow: 1
- Total: ~81 files

Good luck! 🚀