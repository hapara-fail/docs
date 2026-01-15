# hapara.fail Docs

Official documentation for the **hapara.fail** ecosystem, covering our tools, blocklists, and self-hosting guides. This repository hosts main documentation site, built to be clean, fast, and easy to navigate.

**Live Site:** **[https://docs.hapara.fail](https://docs.hapara.fail)**

---

## 🚀 Project Overview

The documentation serves as the central knowledge base for:

- **Project Details:** Information about the website and blocklist initiatives.
- **Self-Hosting:** Comprehensive guides for setting up your own DNS and website instances.
- **Contributing:** Guidelines for the community to get involved.

---

## ✨ Key Features

- **MDX Support:** Rich content with interactive components.
- **Fast Navigation:** Instant page loads and smooth transitions.
- **Full-Text Search:** Powerful search to find information quickly.

---

## 💻 Technology Stack

- **Platform:** [Mintlify](https://mintlify.com/) - Intelligent documentation platform.

---

## 📁 Project Structure

```
├── docs.json           # Mintlify configuration (navigation, theme, etc.)
├── favicon.svg         # Site favicon
├── index.mdx           # Landing page
├── website.mdx         # Website project overview
├── blocklist.mdx       # Blocklist project overview
├── self-hosting/       # Self-hosting guides
│   ├── dns.mdx         # DNS setup guide
│   └── website.mdx     # Website setup guide
├── images/             # Static assets
└── README.md           # This file
```

---

## 🗺️ Routes

- `/` - Home
- `/website` - Website Overview
- `/blocklist` - Blocklist Overview
- `/self-hosting/dns` - DNS Self-Hosting Guide
- `/self-hosting/website` - Website Self-Hosting Guide
- `/contributing` - Contributing Info

---

## 🛠️ Development

### Prerequisites

- Node.js (v18 or higher recommended)
- [Mintlify CLI](https://www.npmjs.com/package/mint)

### Local Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/hapara-fail/docs.git
    cd docs
    ```
2.  **Install Mintlify CLI (global):**
    ```bash
    npm i -g mint
    ```
3.  **Start the local development server:**
    ```bash
    mint dev
    ```
    This command will start the documentation server locally, typically at `http://localhost:3000`.

---

## ☁️ Deployment

Changes are automatically deployed to production via the Mintlify GitHub App when pushing to the `main` branch.

---

## 🤝 Contributing

Contributions are welcome! Please check out our **[Contributing Guidelines](https://github.com/hapara-fail/docs/blob/main/CONTRIBUTING.md)** for more details on how to help improve our documentation.

If you spot an error or have a suggestion:

- **Open an Issue** on GitHub.
- **Submit a Pull Request** with your fixes.
- Join our [Discord server](https://www.hapara.fail/discord) to discuss.

---

## 📄 License

This project is licensed under the terms specified at [www.hapara.fail/license](https://www.hapara.fail/license).
