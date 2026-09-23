PASAN — PORTFOLIO (multi-page)
==============================

FILES
  index.html                     main portfolio (who am i, projects, tracks, red-button gag)
  file-integrity-monitor.html    project detail pages — one per tool
  ssh-brute-force-detector.html
  port-scanner.html
  netsniffer.html
  ssh-log-parser.html
  system-automation-tool.html

HOW IT LINKS
  index.html project cards  ->  each detail page
  detail page "All projects" / "Back to portfolio"  ->  index.html
  detail pages also chain prev/next to each other + link to the GitHub repo

DEPLOY (GitHub Pages, free)
  1. repo named exactly:  PASAN121.github.io
  2. push ALL html files to the main branch root (keep the filenames)
  3. live at https://pasan121.github.io  (~1 min)
  Keep every file in the SAME folder — links are relative.

BEFORE DEPLOYING
  - polish the toolkit README (every page links to the repo)
  - your github avatar is shown on the homepage — make sure it's the one you want
  - test on phone: tracks section swipes, project pages stack fine
