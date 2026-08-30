# Seismic Hazard Resilience Unit (SHRU)
## University of Duhok - College of Engineering
**زانکۆیا دهۆک - کۆلیژا ئەندازیاری - یەکا بەرهەڤدانانا مەترسیا عەرد هەژینێ**

[![Deploy to GitHub Pages](https://github.com/uod-engineering/shru-seismic-unit/actions/workflows/deploy.yml/badge.svg)](https://github.com/uod-engineering/shru-seismic-unit/actions)

Official academic and research portal of the **Seismic Hazard Resilience Unit (SHRU)** at the University of Duhok College of Engineering. Advancing earthquake engineering, geotechnical resilience, regional hazard mapping, and community disaster mitigation in the Kurdistan Region and Northern Iraq.

🌐 **Live Website on GitHub Pages:** [https://shru.uod.ac](https://shru.uod.ac)

---

## 🚀 How to Publish on GitHub Pages (Step-by-Step)

### Option 1: Quick 2-Minute Setup with GitHub
1. Create a **New Repository** on GitHub named `shru-seismic-unit`.
2. Extract this ZIP archive onto your computer.
3. Open your terminal in the extracted folder and run:

```bash
git init
git add .
git commit -m "Initial commit of SHRU University of Duhok portal"
git branch -M main
git remote add origin https://github.com/uod-engineering/shru-seismic-unit.git
git push -u origin main
```

4. In your GitHub repository settings:
   - Go to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, select **GitHub Actions**
5. GitHub will automatically build and publish your website! Your site will be live at:
   **https://uod-engineering.github.io/shru-seismic-unit/**

---

## 📝 Updating Content & Adding Research Papers (Markdown)

This website features a built-in Markdown Content Manager:
1. Open the website and click **"Content Manager / Markdown"** in the top navigation bar.
2. Choose **"New Item"** and select a template (**Research Paper**, **News**, **Announcement**, or **Seismic Bulletin**).
3. Edit the content in live markdown preview, add authors, DOI, PDF link, and tags.
4. Click **"Publish to Website"** (updates locally immediately) and **"Download .md"** or **"Export GitHub Pages Package"** to push to your repository!

### Content Directory Structure:
- `/content/papers/`: Peer-reviewed research papers and technical reports.
- `/content/news/`: Press releases, faculty milestones, and campus instrumentation updates.
- `/content/announcements/`: Conferences, workshops, and calls for papers.
- `/content/bulletins/`: Rapid earthquake advisories and public safety protocols.

---

## 🛠️ Local Development

```bash
# 1. Install dependencies
npm install

# 2. Start local development server
npm run dev

# 3. Build production bundle for static hosting
npm run build
```

---

## 🏛️ Affiliation & Contact
- **Institution:** University of Duhok, College of Engineering
- **Unit:** Seismic Hazard Resilience Unit (SHRU)
- **Location:** Zakho Way, Duhok 42001, Kurdistan Region, Iraq
- **Email:** shru@uod.ac
- **Website:** https://uod.ac
