# git habit tracker

A lightweight, single-file web app for building a consistent Git commit habit — with a daily checklist, commit logger, contribution grid, and a full command reference.


**Live site:** [[Ramita13.github.io/git-habit-tracker](https://ramita13.github.io/git-habit-tracker/)]

---

## what it does

**Tracker tab**
- Daily habit checklist (pull before coding, commit before coffee/Slack/lunch, end-of-day push)
- Commit logger with colour-coded prefixes (`feat:`, `fix:`, `WIP:`, `refactor:`, `chore:`, `docs:`)
- 14-week contribution grid (like GitHub's, but local)
- Live streak counter and weekly commit count
- All data persists in `localStorage` — survives browser close and reopens

**Daily system tab**
- Every command for each phase of the day: start of day, branching, in-progress commits, push, merge, rescue
- Copy button on every command

**Commands tab**
- 11 expandable sections covering ~110 git commands
- Setup, inspection, staging, branching, merging & rebasing, remotes, tags, stashing, undoing, searching, advanced
- Dangerous commands flagged with warnings
- Copy button on every command

---

## how to use

No install. No dependencies. No server.

1. Clone or download the repo
2. Open `index.html` in any browser
3. Or visit the live GitHub Pages URL

```bash
git clone https://github.com/your-username/git-habit-tracker.git
cd git-habit-tracker
# open index.html in your browser
```

---

## storage

Data is saved in the browser's `localStorage`. This means:

- Persists between sessions on the same browser and device
- Not synced across devices (by design — kept simple)
- To avoid data loss, always open from the same browser

---

## stack

- Vanilla HTML, CSS, JavaScript — zero dependencies
- [Geist](https://vercel.com/font) font via Google Fonts
- Hosted via GitHub Pages

---

## deploy your own

Fork this repo, enable GitHub Pages under **Settings → Pages → Deploy from branch → main**, and your instance will be live at:

```
https://your-username.github.io/git-habit-tracker/
```

---

## background

Built as a personal tool while working as an AI/ML Engineer at [Histofy AI](https://histofy.com), developing CheQmate — a computer vision system for automated FFPE tissue block capture deployed at NHS hospitals.

The habit system is designed around evidence building for the Global Talent Visa (Exceptional Promise route), where a consistent GitHub contribution history is a meaningful piece of the portfolio.
