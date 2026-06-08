# Word Drill

A single-file browser app for memorising any text through progressive word-by-word drilling. No install, no dependencies — just open `index.html`.

## How it works

Paste any paragraph and drill each sentence across three escalating levels:

| Level | What you see | What you type |
|-------|-------------|---------------|
| **Full** | Every word visible | First letter of each word |
| **Partial** | 2nd and last letter only, first hidden | First letter of each word |
| **Blind** | All underscores | First letter of each word |

After every 2 sentences, the entire completed portion of the paragraph is shown in **Review** mode (all blank) — type through the whole thing from memory.

If you make **3 or more mistakes** in a Blind or Review phase, that phase replays automatically.

## Controls

- **Type** — first letter of the current word (case-insensitive)
- **‹ Back** — go to the previous phase
- **↺ Restart** — redo the current phase
- **Skip ›** — skip to the next phase
- **Ctrl + Enter** — start drilling from the text input

## Features

- Sentences auto-split on `.` `!` `?` and also at `;` `—` `–` `:` for long sentences
- Numbers treated as words (type the leading digit)
- Punctuation shown inline but never required to be typed
- Summary screen: accuracy, time, mistakes, words/min

## Usage

Open `index.html` in any modern browser. That is it.

Or visit the live version at the GitHub Pages URL for this repo.
