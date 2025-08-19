Thanks for sharing both files. Based on the current state of:

* `README.md` (which should be the project overview and contribution entry point), and
* `intro-behavior-graphs.md` (which should only contain documentation about Behavior Graphs),

I'll now provide corrected versions of both files, fixing the mistake that was noted by Exairnous: moving the **Behavior Graph** content **out of the README** and back into `intro-behavior-graphs.md`, and ensuring the `README.md` contains the correct project-level information including the Docusaurus header.

---

## ✅ Updated `README.md`

````md
---
id: readme
title: Hubs Docs
sidebar_label: Introduction
slug: /
description: Welcome to the Mozilla Hubs documentation site. Learn how to contribute and explore resources related to the Hubs platform.
---

# Mozilla Hubs Documentation

Welcome to the documentation site for [Mozilla Hubs](https://hubs.mozilla.com/), an open source project that enables shared virtual reality experiences in the browser.

This site is built using [Docusaurus 2](https://docusaurus.io/), and aims to provide users, creators, and developers with guidance, reference materials, and tutorials for using and contributing to Hubs.

## 📁 Project Structure

This documentation project includes:

- `docs/` — Markdown files for documentation pages (rendered at [hubs.mozilla.com/docs](https://hubs.mozilla.com/docs))
- `website/` — The Docusaurus site configuration and styling
- `static/` — Static files like images, icons, etc.

## 🧠 Key Concepts

- **Hubs** — Virtual 3D spaces you can enter with a URL and customize via Blender, Spoke, or code.
- **Spoke** — Mozilla’s visual editor for creating 3D scenes.
- **Behavior Graphs** — A system for defining interactions visually via node-based scripting in Blender.
- **Self-Contained Models** — `.glb` files that include geometry, textures, and behavior logic.

## 🚀 Getting Started

If you’re new to Hubs and just want to get started:

- Learn about [Creating Scenes with Spoke](./spoke-intro.md)
- Explore [Behavior Graphs for interactivity](./intro-behavior-graphs.md)
- Understand [Hubs Rooms and Avatars](./rooms-and-avatars.md)

## 📥 Contributing

Contributions are welcome! If you're new to open source or the Hubs ecosystem:

- See our [Contribution Guidelines](./policies-procedures-guidelines-public/commit-message-guidelines.md)
- Read our [Docs Contribution Process](./docs-contribution-guidelines.md)
- Join us in a [Community Collaboration Session](https://github.com/MozillaReality)

To contribute:

```bash
# Clone the repo
git clone https://github.com/MozillaReality/hubs-docs.git
cd hubs-docs

# Install dependencies
npm install

# Run locally
npm run start
````

## 📚 Docusaurus Notes

This site is built with **Docusaurus v2**, which enables:

* Markdown-based docs
* Sidebar navigation
* Custom themes and styling
* Hot reload development server

Check `docusaurus.config.js` and the `sidebars.js` for configuration.

---

> For issues or ideas, open a [GitHub Issue](https://github.com/MozillaReality/hubs-docs/issues).

