# Claude Memory Template

A personal `CLAUDE.md` template that gives Claude Code persistent memory about who you are, how you write, and what you're working on — without re-explaining yourself every session.

---

## What problem this solves

Every time you open Claude Code, it starts fresh. It doesn't know your name, your job, how you like to communicate, or what you're working on. You end up re-explaining yourself constantly.

This template fixes that. Drop one file in your home folder and Claude remembers everything — permanently.

---

## What you'll need

- [Claude Code](https://claude.ai/code) installed (free to start)
- 15–20 minutes to fill in the template

That's it. No coding required.

---

## Setup (step by step)

### Step 1: Download the template
Click the green **Code** button above → **Download ZIP** → unzip it.

### Step 2: Open `CLAUDE.md` in any text editor
TextEdit, Notes, VS Code, whatever you have. You'll see sections with `[placeholders in brackets]` — replace each one with your own info.

**What to fill in:**

| Section | What to write |
|---|---|
| Who I Am | Your name, location, career background, current focus |
| Key metrics / wins | Real numbers from your work — Claude uses these for resumes, bios, pitches |
| How to Communicate | Leave the defaults or adjust to your preference |
| My Writing Voice | Describe how you sound — formal? casual? direct? storytelling? |
| Never Words | Words and phrases that feel wrong in your voice |
| Active Projects | What you're working on right now — job search, product, side project |

### Step 3: Move the file to your home folder
Once filled in, move `CLAUDE.md` to `~/` (your home folder — the one with Desktop, Documents, Downloads in it).

On a Mac: open Finder → Go → Home → drop the file there.

Or in terminal:
```bash
mv ~/Downloads/CLAUDE.md ~/CLAUDE.md
```

### Step 4: Open Claude Code
That's it. Claude will read the file automatically from now on. Test it by asking: *"What do you know about me?"*

---

## Pro tip: port your Claude.ai memory

Already using Claude.ai (the website)? You can export everything it knows about you and import it here:

1. Go to **claude.ai → Settings → Privacy → Export data**
2. Download the ZIP — you'll get it by email within a few minutes
3. Open Claude Code, share the file path, and say: *"Read this export and save the key facts to memory"*

Claude will pull your history, extract what matters, and save it automatically.

---

## Bonus: use Claude to source jobs automatically

Once your profile is set up, you can use Claude Code + [Ruflo](https://github.com/ruvnet/ruflo) to search job boards and surface relevant roles without logging into LinkedIn every day.

**Install Ruflo:**
```bash
curl -fsSL https://cdn.jsdelivr.net/gh/ruvnet/ruflo@main/scripts/install.sh | bash
```

**Then ask Claude:**
> *"Search for Senior PMM roles that match my background — remote or San Diego, $180K+, no fixed hybrid schedules"*

Claude will search public job boards (Greenhouse, Lever, Indeed, Wellfound) and return a list tailored to your profile. Run it anytime for a fresh pull.

---

## What's included

- `CLAUDE.md` — the template to fill in and drop in your home folder

---

## About

Built by [Diana Golduber](https://www.linkedin.com/in/dianagolduber) — PMM with 12+ years at Google and Meta, currently exploring what it looks like to build a persistent AI memory layer for non-technical people.

Questions or suggestions → open an issue or connect on LinkedIn.
