# Contributing Guidelines

First off, thank you for considering contributing to the **hapara.fail documentation**. This project relies on community contributions to remain accurate, helpful, and up-to-date.

Whether you are fixing a typo, adding a new guide, or improving the layout, your help is vital.

## 🐛 Reporting Issues

We have simplified our reporting process. Please use the direct links below to **open an issue** using the correct template.

### 1. Reporting Bugs / Errors

If a page is broken, information is incorrect, or you spot a typo:

- **[Click here to open a Bug Report](https://github.com/hapara-fail/docs/issues/new?template=bug_report.md)**
- **Crucial:** Please tell us which page is affected and provide as much detail as possible.

### 2. Suggesting Features & Content

If you have an idea for a new guide, a section improvement, or a design change:

- **[Click here to open a Feature Request](https://github.com/hapara-fail/docs/issues/new?template=feature_request.md)**
- We love community ideas! If you have specific text or structure in mind, please include it.

---

## 🛠️ Submitting Changes (Pull Requests)

We welcome direct code contributions. Whether you are editing markdown content or Mintlify configuration, please follow these guidelines.

### 1. Project Structure

The project is built on **Mintlify**.

- **`docs.json`**: Configuration file for navigation, theme, and settings.
- **`*.mdx`**: Documentation pages written in MDX (Markdown + React components).
- **`images/`**: Static assets for the documentation.

### 2. How to Contribute

1.  **Fork** the repository to your own GitHub account.
2.  **Create a Branch** for your specific change (e.g., `fix-dns-guide` or `add-faq-section`).
3.  **Make your changes.**
    - If adding a new page, remember to update `docs.json` navigation.
4.  **Test Locally:**
    - Install Mintlify CLI: `npm i -g mint` (if not already installed).
    - Run `mint dev` to start the local development server.
    - Verify your changes at `http://127.0.0.1:3000`.
5.  **Commit** your changes with a clear message:
    - _Good:_ "Update DNS self-hosting guide with Unbound instructions"
    - _Bad:_ "update docs"
6.  **Push** to your branch and open a **Pull Request**.

### 3. Style Guidelines

- **Content:** Clear, concise, and easy to understand. Use proper headings and formatting.
- **Tone:** Professional yet accessible to students and administrators.
- **Accuracy:** Ensure all commands and technical details are verified.

---

## 🤝 Code of Conduct

We value accuracy, privacy, and collaboration. Please ensure your interactions—whether in issues, pull requests, or Discord—are respectful and constructive. By participating, you are expected to uphold our **[Code of Conduct](https://github.com/hapara-fail/docs/blob/main/CODE_OF_CONDUCT.md)**.

## 📜 License

By contributing to hapara.fail, you agree that your contributions will be licensed under the same **GNU General Public License v3.0 (GPLv3)** that covers the project. Details can be found at [www.hapara.fail/license](https://www.hapara.fail/license).
