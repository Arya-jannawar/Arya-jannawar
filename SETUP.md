# 🚀 Shipping NEON.OS v2.0 — your new GitHub profile

A bold, animated "mission-control" profile: synthwave banner with a flowing
perspective grid, a live-typing terminal, glowing project cards, morphing wave
footer, real-time stat telemetry and a contribution snake.

## 1. Create the profile repo

1. Go to <https://github.com/new>
2. Repository name must be **exactly**: `Arya-jannawar` (same as your username)
3. Visibility: **Public** ✅ · check "Add a README file" ✅
4. Create.

GitHub now treats this repo's README as your profile page.

## 2. Push these files into it

Copy the whole contents of this folder into the repo (keeping the structure):

```
README.md
SETUP.md                  (optional — keep or delete)
assets/svg/
  header-banner.svg       ← animated synthwave banner
  terminal.svg            ← animated whoami terminal
  divider.svg             ← energy-beam section divider
  project-metromind.svg   ← glowing project card
  project-trustlens.svg   ← glowing project card
  project-pharmacy.svg    ← glowing project card
  footer-wave.svg         ← morphing wave footer
.github/workflows/snake.yml  ← generates the contribution snake
```

From this folder:

```bash
git clone https://github.com/Arya-jannawar/Arya-jannawar.git
cd Arya-jannawar
# copy the files in (or just drag-and-drop them on github.com — same result)
git add . && git commit -m "NEON.OS v2.0" && git push
```

## 3. Activate the snake 🐍

1. Open the repo → **Actions** tab → if prompted, click **"I understand my workflows, go ahead and enable them"**
2. Select **🐍 Generate Snake** → **Run workflow** → Run.
3. After ~1 minute it publishes the snake to an `output` branch and the
   SNAKE.EXE section of your README comes alive. It re-runs daily by itself.

## 4. Fill the TODOs (5 minutes)

Open `README.md` and search for **TODO-**:

- `TODO-LINKEDIN` → your LinkedIn profile URL
- `TODO-EMAIL` → your email address (in the `mailto:` link)

Optional personalization (all clearly marked in the files):

- `assets/svg/terminal.svg` — the lines the terminal "types"
- `assets/svg/project-*.svg` — descriptions, tech tags, status chips
- `assets/svg/header-banner.svg` — the `// status:` line under your name
- `README.md` — the typing-animation lines (the `lines=` parameter of the typing widget URL)

## 5. Care & feeding

- **Stats cards not loading?** They come from community-hosted services; if one
  ever goes down, the fix is deploying your own instance (free):
  [github-readme-stats](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance),
  [activity graph](https://github.com/Ashutosh00710/github-readme-activity-graph),
  [trophies](https://github.com/ryo-ma/github-profile-trophy). The URLs currently
  in the README point at instances verified working as of Oct 2026.
- **Skill icons**: edit the `i=` list in the two `skillicons.dev` URLs
  (any of: <https://github.com/tandpfun/skill-icons#available-icons>).
- **New pinned repos**: pin them on your profile ("Customize your pins") —
  and consider promoting one into a `FEATURED_BUILDS` card by copying a card
  SVG and swapping the text.

That's it — go make visitors stop scrolling. ⚡
