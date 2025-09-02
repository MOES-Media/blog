# MOES-Media Dev Blog

Technical blog covering Strapi development, plugin creation, and modern web development practices.

🔗 **Live Blog**: https://moes-media.github.io/blog

## Repository Structure

```
blog/
├── site/                    # Astro blog site
│   ├── src/content/blog/   # Blog posts
│   ├── src/components/     # Astro components
│   └── ...                 # Other Astro files
├── code/                   # Code samples from articles
│   ├── part-1-setup/      # From Script to Screen: Part 1
│   ├── part-2-plugin/     # From Script to Screen: Part 2
│   └── ...
└── README.md              # This file
```

## Series: From Script to Screen

Building a movie collection plugin for Strapi from scratch.

- **Part 1**: [Setting up Strapi](./site/src/content/blog/from-script-to-screen-part-1.md) | [Code](./code/from-script-to-screen-part-1/)
- Part 2: Coming soon...

## Development

To run the blog locally:

```bash
cd site
pnpm install
pnpm dev
```

## Deployment

The blog is automatically deployed to GitHub Pages via GitHub Actions when pushing to the `main` branch.