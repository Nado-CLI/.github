<p align="center">
  <img src="https://raw.githubusercontent.com/Nado-CLI/.github/master/nado-logo.png" alt="nado logo" width="700"/>
</p>

<h1 align="center">nado</h1>

> A modern, minimal Python CLI for modular project and package management.

---

## 🧠 About

**nado** is a modern command-line tool designed to simplify the way Python developers structure, scaffold, and compose their projects. Inspired by tools like Composer and npm, but built specifically for Python's ecosystem with a focus on:

- **GitHub-based packages**  
- **Modular design philosophy**  
- **Async-first and API-first workflows**  
- **Developer-first ergonomics**

It enables teams and individuals to share reusable components, bootstrap projects, and manage dependencies — all through a minimal and intuitive interface.

---

## 🚀 Core Philosophy

- **Simplicity First**  
  Clear commands and clean configuration, without unnecessary abstraction.

- **Decentralized by Default**  
  Instead of relying on a central package registry like PyPI, `nado` fetches packages from GitHub, making it easier to build your own ecosystem.

- **Composable & Scalable**  
  Whether you're building a microservice, CLI tool, or full-stack app — `nado` helps you compose your project from small, reusable parts.

---

## 🧩 Key Features

- 📦 GitHub-powered `require` system  
- 🧱 Project scaffolding and module templates  
- 🧠 Smart local caching and version tracking  
- 🔒 Lockfile and reproducible builds  
- 🛠 Plug-and-play development style  

---

## 🗂 Project Structure

A typical `nado`-based project may contain:

- `nado.json` – Main configuration file  
- `.nado/vendor` – Downloaded packages from GitHub  
- `nado.lock` – Dependency lockfile  

No `setup.py`, no boilerplate. Just structured, scoped packages.

---

## 🛣 Roadmap (WIP)

- [x] `nado init` for project bootstrapping  
- [x] `nado require <pkg>` to fetch from GitHub  
- [ ] Semantic versioning support via Git tags  
- [ ] Template and scaffold engine  
- [ ] Plugin system for extending commands  
- [ ] Web-based package browser (future idea)

---

## 👥 Who is it for?

- Python developers who want **modular** and **modern** tooling  
- Teams building reusable internal components  
- Framework creators who need CLI-based workflows  
- Developers tired of bloated config and slow scaffolding tools

---

## 🌍 Repository Layout

This tool is part of the [**Nado-CLI** GitHub organization](https://github.com/Nado-CLI), where packages like `app`, `auth`, `db`, and more are hosted as GitHub repositories.  
Each package can be required into your project using `nado`.

---

## ⚡️ License

MIT – Open, simple, and for the community.
