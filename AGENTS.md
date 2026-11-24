# AGENTS.md — player-facing site

This repository is public and holds the site GitHub Pages serves at <https://eliminize.github.io/>.
It is the front page of the game: the pitch a stranger reads first, and the page every other public
surface (the organization profile included) links to.

- **Enough to decide, not the reference.** Say what the game is, in the setting's voice (the Ministry of
  Leisure briefing a new franchise holder), with the facts that make a reader want a match. The rules
  themselves live with the game; the site may quote headline numbers, never the exceptions or edge cases.
- **Change it when the headline changes**, not whenever a number moves. When a rule the site names changes,
  correct it here in the same piece of work.
- **Write for players**, never developers: no issue references, plans, risks, playtests, roadmap, and no
  link to a private repository. Describe the game as it is played today.
- **No build.** Plain HTML and CSS, no JavaScript unless a feature needs it. The palette and font stack
  copy the game's (`--bg`, `--acid`, `--hot`, Bahnschrift…), so both look like one broadcast.
- **Images** live in `assets/`, referenced relatively (root-relative in `404.html`, which Pages serves at
  any path). Social previews (`og:image`) need absolute `https://eliminize.github.io/…` URLs.
- **The organization profile stays short** and points here; do not grow it back into a second copy.
- **`main` is the published branch.** Commit on it directly unless the user asks for a branch or a pull
  request; push only when the user asks.
