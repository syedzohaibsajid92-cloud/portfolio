# Syed Zohaib Sajid - Portfolio

Plain HTML, CSS and JavaScript. No build step and no dependencies (only Google Fonts).

## Files
- `index.html` - the whole site (styles and scripts inside)
- `assets/` - screenshots, car photo, brand film, resume PDF

## Run on your computer
Open `index.html` in a browser. Or, for a local server: `python -m http.server 8000` then visit http://localhost:8000

## Edit
Near the top of the `<script>`, the `CONFIG` block holds your name, email, LinkedIn, GitHub and project links.
Add your LinkedIn URL to `linkedin`, and a GitHub URL to `github`. Empty links stay hidden.
Project links go in `links.pak`, `links.car`, `links.speed` as `["Label","https://..."]`.
To change the resume, replace `assets/Syed_Zohaib_Sajid_CV.pdf` and `assets/cv.png`.

## Deploy (Vercel)
1. Put these files in a new GitHub repository (`index.html` and `assets` at the top level).
2. Vercel > Add New > Project > pick the repository > Deploy. No settings needed.
