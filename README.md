# Developer Portfolio & Blog

A high-performance, professional portfolio website built with **Astro**, **Tailwind CSS**, and **Markdown**. Hosted for free on GitHub Pages.

## 🚀 Quick Start

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Run local development server:**
   ```sh
   npm run dev
   ```
   Open `http://localhost:4321` to see your site.

3. **Build for production:**
   ```sh
   npm run build
   ```

## 🛠 Customization

### 1. Site Metadata
Update `src/consts.ts` to change the site title and description used for SEO and the header.

### 2. Branding & Config
Open `astro.config.mjs` and update:
- `site`: Your GitHub Pages URL (e.g., `https://yourusername.github.io`).
- `base`: Your repository name if not using a custom domain (e.g., `/my-portfolio/`).

### 3. Homepage Content
Edit `src/pages/index.astro` to update:
- Hero section text and profile image.
- Technical Skills list.
- Featured Projects.

### 4. Blog Posts
Add or edit Markdown files in `src/content/blog/`. Each file should have frontmatter like:
```yaml
---
title: 'My First Post'
description: 'A brief description'
pubDate: 'Jul 08 2022'
heroImage: '/blog-placeholder-3.jpg'
---
```

## 🌐 Deployment to GitHub Pages

This project includes a GitHub Action for automated deployment.

1. **Create a GitHub Repository** and push your code:
   ```sh
   git remote add origin https://github.com/yourusername/your-repo.git
   git branch -M main
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repo on GitHub.
   - Settings > Pages.
   - Under **Build and deployment > Source**, select **GitHub Actions**.

3. **Automatic Updates:**
   Every time you push to the `main` branch, the site will automatically rebuild and redeploy.

## 📁 Project Structure

- `src/pages/`: Your site routes (Home, Blog, About).
- `src/layouts/`: Reusable page wrappers.
- `src/components/`: UI components (Navbar, Footer, etc.).
- `src/content/blog/`: Your blog posts in Markdown.
- `public/`: Static assets like images and favicons.

---
Built with ❤️ using [Astro](https://astro.build/)
