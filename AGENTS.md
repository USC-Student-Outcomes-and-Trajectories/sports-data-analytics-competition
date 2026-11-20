# Agent Operating Guidelines: USC Sports Data Analytics Competition Website

This repository hosts the official live website for the **USC Marshall Sports Data Analytics Competition**, served via GitHub Pages at:
https://usc-student-outcomes-and-trajectories.github.io/sports-data-analytics-competition/

---

## 1. Linked Sibling Repository

This website works in tandem with the primary competition planning and documents repository:
* **Sibling Planning Repo:** `/Users/milanmiric/Documents/Admin Work Documents/MSBA - Baseketball Case Competition`
* **Remote:** `git@github.com:USC-Student-Outcomes-and-Trajectories/msba-sports-data-analytics-competition.git`

---

## 2. Mandatory Dual-Push & Synchronization Protocol

**CRITICAL REQUIREMENT:** Whenever website updates are made or when planning documents change, **ALWAYS ensure BOTH repositories are committed, pushed, and in sync.**

1. **Website Repository:**
   * Main entrypoint: `index.html`
   * Assets: `assets/` (images, stylesheets, logos, favicons)
   * Deploy branch: `main` (served via GitHub Pages)
2. **Pushing Changes:**
   * When modifying `index.html` or assets, commit and push to `origin main`.
   * Also ensure matching updates (dates, links, PDFs) are committed and pushed to the sibling repo (`MSBA - Baseketball Case Competition`).
