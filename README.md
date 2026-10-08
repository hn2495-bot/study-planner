# Study Planner

A one-screen study dashboard for students: today's to-dos, a timeline (Gantt chart) of every course, and exam countdowns. It's a single HTML file — no account, no server, no install.

**Use it:** open the GitHub Pages link for this repo (see "Publish" below), or download `index.html` and open it in your browser.

## Features

- **Today** — every task due to be worked on today, as color-coded cards with a Done button. Multi-day tasks get a "Done for today" button and keep showing up each day until the whole task is finished.
- **Timeline** — one row per course, three weeks at a time. Click a bar to mark it done, double-click for details. Each day shows its total workload in hours (orange above 3h).
- **One-click tasks** — `+Review`, `+Prep` and `+Self-study` add a 1-hour task; with class days set, Prep/Review are due right before the next class.
- **Exam countdown** — the nearest upcoming exam per course, highlighted in the final week.
- **Repeating tasks** — e.g. "Review every Mon/Wed until the end of term".
- **Semesters** — separate tabs (Fall 2026, Spring 2027, …).
- **Weekly topics** — list a syllabus's topics, including ones whose week isn't announced yet.
- **Custom background** for the Today panel, with adjustable opacity.
- Light and dark mode follow your system setting.

Task colors: Prep (pink), Review (blue), Self-study (green), Assignment (orange), Exam (purple), Done (gray).

## Your data

Everything is stored in your own browser (`localStorage`). Nothing is sent anywhere, and each person who opens the page gets their own empty dashboard.

That also means:
- Data is tied to **one browser on one computer**. Clearing site data or using a private window loses it.
- Use **Backup → Download backup** regularly. Restore the file on another computer or browser to move your data.

## Publish your own copy (GitHub Pages)

1. Create a new public repository on GitHub and upload `index.html`, `README.md` and `LICENSE`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute, the site is live at `https://<your-username>.github.io/<repo-name>/`.

**Tip:** in Chrome, open the page and choose ⋮ → *Cast, save and share* → *Install page as app* to get a desktop app icon.

## License

MIT — see `LICENSE`.
