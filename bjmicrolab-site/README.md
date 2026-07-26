# BJ Micro Lab — Website

Plain HTML/CSS/JS site, ready to open in VS Code (Live Server extension recommended).

## Structure
```
index.html              Home
about.html               About
services.html            Services overview (grid → links to detail pages)
services/
  genetic-analysis.html
  microbial-testing.html
  pcr-amplification.html
  dna-rna-extraction.html
  cell-culture.html
  sequencing-services.html
team.html                Team
contact.html             Contact (form + map)
css/style.css            All styling + light/dark theme tokens
js/main.js                Theme toggle, mobile nav, scroll reveal, form demo
```

## About the team photos
bjmicrolab.pk blocks automated access (its robots.txt disallows scraping), so I wasn't able to pull the real team photos from the live site. Team members are listed with their real names and roles, using initials-based avatar placeholders in the meantime. Drop real photos into `/images` and swap them into `team.html` (and the About page) whenever you have them — happy to wire that up for you too.

## Dark / light mode
Bottom-right toggle button switches themes instantly. It follows the visitor's system preference by default (no cookies/local storage used).

## Social links
Facebook, Instagram, and YouTube in the footer are linked to BJ Micro Lab's real accounts. Update if any of these change.

## Contact info used
- Address: Abdur Rehman Plaza, 2nd Floor, Gulzar-e-Quaid, Rawalpindi, Pakistan
- Phone: +92 331 2411144 / 051-5971915
- Email: info.bjmicrolab@gmail.com

Update the contact form's submit handler in `js/main.js` to connect it to a real backend or form service (e.g. Formspree) — right now it's a front-end demo only.
