# Hubs Documentation

This repository contains the documentation for [Mozilla Hubs](https://hubs.mozilla.com/) — an open-source platform for shared virtual reality spaces on the web. This documentation is intended for contributors, creators, developers, and community members who want to understand, extend, or contribute to the Hubs ecosystem.

📚 You can view the live version of this documentation at:  
👉 https://hubs.mozilla.com/docs

---

## 🧭 Overview

This documentation includes:

- Tutorials and guides for setting up and using Hubs
- Technical documentation for Hubs architecture and components
- Creator guides for building custom scenes and avatars
- Details on Spoke (scene editor), Blender pipelines, and Hubs Cloud
- Experimental features like Behavior Graphs and scripting

The site is built using [Docusaurus](https://docusaurus.io/), a static site generator.

---

## 🛠 Contributing to the Docs

We welcome contributions from the community!

### 📁 Cloning the repo

```bash
git clone https://github.com/mozilla/hubs-docs.git
cd hubs-docs
npm install
npm run start
````

This will run a local dev server at `http://localhost:3000`.

### 🌿 Creating a Branch

Create a new branch for your edits:

```bash
git checkout -b my-docs-update
```

### ✍️ Editing Documentation Pages

Documentation lives in the `docs/` directory and is written in **Markdown** (`.md`) files with a **Docusaurus frontmatter block** at the top.

Each file includes a YAML header block that defines metadata such as the page ID, title, and sidebar ordering.

Example:

```yaml
---
id: intro-behavior-graphs
title: Introduction to Behavior Graphs
description: Learn how to use Behavior Graphs in Blender to add interactivity to Hubs scenes.
sidebar_position: 1
---
```

⚠️ **Do not remove or modify these headers unless necessary.** They are critical for Docusaurus to render the site correctly.

### 🧠 Docusaurus Frontmatter Explained

The section between `---` lines at the top of every Markdown file is called the **YAML frontmatter**. It defines important metadata for Docusaurus.

Common fields include:

| Field              | Purpose                                                      |
| ------------------ | ------------------------------------------------------------ |
| `id`               | Unique identifier for the page (used for linking/navigation) |
| `title`            | The visible title of the page                                |
| `description`      | Optional summary (used for search, SEO, etc.)                |
| `sidebar_position` | Determines order in sidebar                                  |

This YAML frontmatter **is not Markdown**, so be sure to maintain proper indentation and format.

---

## 🚀 Submitting a Pull Request

When your edits are ready:

```bash
git add .
git commit -m "Update documentation for behavior graphs"
git push origin my-docs-update
```

Then open a Pull Request (PR) against the `main` or appropriate working branch.

We recommend including screenshots (if visual) and a summary of your changes. PRs may be reviewed by community maintainers.

---

## 🧪 Local Preview / Development

To preview your changes:

```bash
npm run start
```

The docs will be served at `http://localhost:3000` and automatically refresh on edits.

---

## 📎 Documentation Structure

* `docs/` — All documentation Markdown files
* `static/` — Images and static assets used in docs
* `sidebars.js` — Defines sidebar structure
* `docusaurus.config.js` — Site-level configuration

---

## 🤝 Join the Community

* [Hubs Discord](https://discord.gg/VvRKJmYz6w)
* [GitHub Discussions](https://github.com/mozilla/hubs/discussions)
* [Community Collaboration Calendar](https://github.com/mozilla/hubs/wiki)

We hold weekly Community Sessions for contributors to work on the docs together — feel free to join!

---

## 🧼 Style & Formatting Guidelines

* Use clear, concise language
* Prefer active voice
* Use code blocks (` ```js `) for code
* Include screenshots where helpful
* Break long sections into logical headings
* Use Markdown best practices (headings, lists, links)

---

## ✅ License

This project is licensed under the [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).

---

*Thank you for helping make the Hubs documentation better!*

