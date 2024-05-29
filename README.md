# LitExplorer

## Getting Started

Follow these steps to host LitExplorer with your own literature collection:

1. Clone this repository
2. Run `npm install`
3. Replace `public/references.bib` with your literature collection
4. Add your images to `public/img/thumbnail` and `public/img/raw`
5. Run `npm run dev` to host the site locally

### Build and Deploy

Run `npm run build` to build the site to `dist`, and host the contents.

### Build and Deploy with GitHub Pages

A GitHub deploy action is included in `.github/workflows/deploy.yaml`, for hosting with GitHub Pages. This action will deploy the site after each pushed commit to `main`. Make sure that your GitHub repository has GitHub Pages enabled, and configured to host with GitHub Actions.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Svelte](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode).
