# nsite-profile-page

A profile page you can publish [via nsite](https://hzrd149.github.io/nsite-manager/) styled like the Primal profile page and automatically displaying your latest repositories.

## Features

- Displays your GitHub repositories in he style of the Primal profile page
- Auto-updates repository data every hour via GitHub Actions
- Responsive design for mobile and desktop
- Shows repo stats (stars, forks, issues, watchers)
- Filters out forked repositories from display

## Setup

1. Fork or clone this repository
2. Update the GitHub username in:
   - `.github/workflows/update-repos.yml` (line 30)
   - `index.html` (lines 390 and 405)
3. Customize profile information in `index.html`:
   - Profile name, bio, and links
   - Profile and banner images
4. Enable GitHub Actions in your repository settings
5. Deploy to GitHub Pages or any static hosting service
