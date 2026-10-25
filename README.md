# Rachel A. Bryant – academic website

A small, plain-HTML personal site: home page with photo, a three-line bio and
a link to your CV; a research page with job market paper, working papers and
work in progress; and a teaching page. No build step, no JavaScript. Edit the
HTML files directly on GitHub and the site updates.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page |
| `research.html` | Research page |
| `teaching.html` | Teaching page |
| `style.css` | Colours, fonts and layout. Edit the values at the top to change the look. |
| `cv.pdf` | Your CV (October 2026 version). Upload a newer one with the same name whenever you update it. |
| `images/photo.jpg` | Your photo, cropped square. To change it, upload a square image with the same name. |
| `papers/Bryant_JMP.pdf` | Your job market paper. Upload a newer draft with the same name to replace it. Other paper PDFs, slides and syllabi go in this folder too. |
| `.nojekyll` | Tells GitHub not to run its Jekyll processor. Optional; if it does not come along when you upload, nothing breaks. |

## Publish on GitHub Pages

1. Sign in to GitHub (create a free account at github.com if you don't have one).
   Note your username.
2. Create a new **public** repository named exactly `USERNAME.github.io`, with your
   username in place of `USERNAME`. The name matters: that is what makes GitHub
   serve it as a website. Tick "Add a README file" so the repository is not empty.
3. On the new repository's page choose **Add file → Upload files**, drag in
   everything from this folder (including the `images` and `papers` folders),
   and click **Commit changes**.
4. Wait a minute or two, then open `https://USERNAME.github.io` in your browser.

If nothing appears after a few minutes, open the repository's **Settings →
Pages** and make sure **Build and deployment** is set to deploy from the `main`
branch, folder `/ (root)`.

Two things that trip people up: file names are case-sensitive on GitHub
(`index.html`, not `Index.html`), and `index.html` must sit at the top level of
the repository, not inside a subfolder.

## Still to fill in

Each of these is marked with an `EDIT:` comment in the HTML, so you can search
the file for `EDIT:` to find the spot.

- `research.html`: the "about X service jobs" figure in the job market paper
  abstract (still a placeholder in the CV); the year of the current draft of
  the TIF paper; and coauthors' full names if you prefer them to initials.
- `teaching.html`: confirm the terms for Intermediate Macroeconomics.
- The "latest version" link inside the job market paper PDF still points to a
  placeholder. Once the site is live, set it to
  `https://USERNAME.github.io/papers/Bryant_JMP.pdf`.

## Update later

On GitHub, open the file you want to change, click the pencil icon, edit, and
click **Commit changes**. The live site refreshes within a minute or two. To
replace a PDF or photo, upload the new file with the same name. Remember to
bump the "Last updated" line in the footer of each page when you post a draft.

## Optional: your own domain

If you own a domain, add a file named `CNAME` containing just the domain (for
example `www.rachelbryant.com`), then follow GitHub's guide to custom domains for
the DNS settings at your registrar.
