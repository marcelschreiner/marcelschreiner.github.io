# &lt;ms/&gt; CDN - Content Delivery Network

[![pages-build-deployment](https://github.com/marcelschreiner/marcelschreiner.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/marcelschreiner/marcelschreiner.github.io/actions/workflows/pages/pages-build-deployment)
[![HitCount](https://hits.dwyl.com/marcelschreiner/marcelschreiner.github.io.svg?style=flat)](http://hits.dwyl.com/marcelschreiner/marcelschreiner.github.io)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=bugs)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=marcelschreiner_marcelschreiner.github.io&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)

<br />

Welcome to the **&lt;ms/&gt; CDN** — the central static asset repository of [marcelschreiner.ch](https://marcelschreiner.ch).

This repository is deployed via **GitHub Pages** and serves as a lightweight  
**Content Delivery Network (CDN)** for all projects, websites, and media  
created by **Marcel Schreiner – Code, Design & Engineering**.

## 📂 Structure
```
democlient/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── fonts/
│
├── images/
│   ├── products/
│   ├── blog/
│   ├── logos/
│   ├── landing/
│   └── ui/
│
└── media/
    ├── videos/
    ├── audio/
    └── downloads/
```

Each project/client follows this same structure  
to keep all assets organized and reusable across websites.

## 🧩 Purpose

- Unified storage and versioning of static files  
- Public delivery through GitHub Pages (`https://cdn.marcelschreiner.ch/...`)  
- Shared branding and UI assets between multiple projects  
- Clean caching strategy for reusable files

## ⚙️ Deployment

GitHub Pages automatically publishes the content of the **`main` branch**.

After every commit, the latest version is available here:
> Changes propagate automatically within a few seconds.

## 🧠 Guidelines

- Only static files (HTML, CSS, JS, fonts, images, videos, PDFs, etc.)  
- No dynamic scripts or server-side code  
- Do not upload personal or sensitive content  
- Use lowercase file names with `-` or `_` separators

## 🧰 License & Credits

© [Marcel Schreiner](https://marcelschreiner.ch)  
All hosted assets (images, icons, fonts, media, and design elements) are protected by copyright  
and may not be reused or redistributed without permission.

All structural and meta files (such as `README.md`, `index.html`, `.gitkeep`, or configuration files)  
are provided for reference and may be freely reused or adapted.

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/summary/new_code?id=marcelschreiner_marcelschreiner.github.io)
