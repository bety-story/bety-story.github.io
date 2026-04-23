# bety-story

Astro-based project for Bety's story, configured for automatic deployment to GitHub Pages.

## 🚀 Getting Started

This project uses `pnpm` as its package manager.

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build
```

## 🌐 Deployment

The project is configured to automatically deploy to **GitHub Pages** (`https://bety-story.github.io`) using GitHub Actions whenever changes are pushed to the `main` branch.

Configuration details:
- **Site URL**: `https://bety-story.github.io`
- **Workflow**: `.github/workflows/deploy.yaml`

## 🛠 Project Structure

```text
/
├── .github/workflows/ # Deployment workflows
├── public/           # Static assets
├── src/
│   └── pages/        # Website pages
├── astro.config.mjs  # Astro configuration
└── package.json      # Project dependencies and scripts
```

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with 💖 and ☕ by <b>Anthonius Munthi</b><br/>
  ✨ <i>"Building digital memories, one commit at a time"</i> ✨<br/>
  🚀 💎 💻 🌸
</p>
