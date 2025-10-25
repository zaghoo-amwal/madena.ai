# Madena AI Website

This is the official static website for **Madena AI — Arabic Alignment Lab**.

## 🚀 Deployment on GitHub Pages

1. Create a new public repository (e.g., `madena.ai`).
2. Upload the contents of this ZIP (index.html and README.md).
3. Go to **Settings → Pages** and under **Build and deployment**, choose `Deploy from a branch` → `main` → `/ (root)`.
4. In **Custom domain**, enter `madena.ai`. GitHub will create a CNAME file automatically.
5. In **Namecheap → Advanced DNS**, add:
   - A records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - CNAME for `www` → `<your-username>.github.io`
6. Wait a few minutes, then visit https://madena.ai to see your live site.

