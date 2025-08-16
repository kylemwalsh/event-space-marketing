# Event Space Marketing

A modern marketing website built with Astro.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Deployment

This project is configured to automatically deploy to GitHub Pages when changes are pushed to the `main` or `master` branch.

### Setup Instructions:

1. **Update the Astro config**: Replace `YOUR_USERNAME` in `astro.config.mjs` with your actual GitHub username.

2. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub
   - Navigate to "Pages" in the sidebar
   - Under "Source", select "GitHub Actions"

3. **Push your changes**:
   ```bash
   git add .
   git commit -m "Add GitHub Pages deployment"
   git push origin main
   ```

4. **Monitor deployment**: Check the "Actions" tab in your GitHub repository to see the deployment progress.

### Manual Deployment

If you need to deploy manually:

```bash
npm run build
# The built files will be in the `dist/` directory
```

## 🛠️ Built With

- [Astro](https://astro.build/) - The web framework for content-driven websites
- [GitHub Actions](https://github.com/features/actions) - CI/CD pipeline
- [GitHub Pages](https://pages.github.com/) - Static site hosting

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
