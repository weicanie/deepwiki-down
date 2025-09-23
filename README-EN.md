# deepwiki-get

Convert the deepwiki site to md files.

## 📖 Working Principle

DeepWiki is built with Next.js, and the RSC responses of the site already contain the complete Markdown content. The project directly acquires the site's md text by intercepting RSC requests.

**RSC Interception**

- Intercepts RSC requests
- Extracts Markdown content

**Spider Crawling (Comparison)**

- Visits web pages
- Downloads HTML
- Parses DOM
- Converts HTML to Markdown
- Routing
- ...

## 🚀 Instructions for Use

### Install Dependencies

```bash
# Install Python dependencies uv sync
# Install Playwright Browser python -m playwright install chromium
```

### Basic Usage

```bash
python -m src.interface.cli wiki \
"https://deepwiki.com/username/repository" \
--o "/path/to/output"
```

---

## 🤝 Contribution Guide

1. Fork this repository.
2. Create a feature branch (`git checkout -b feature/amazing-feature`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/amazing-feature`).
5. Open a Pull Request.
