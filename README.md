# Monica Renneke — GitHub Pages portfolio

Minimal public website containing **approved public writing-sample PDFs only**. This ZIP is a starter package, not a live website. The original Google Drive files and historically distributed resume links remain unchanged.

## URLs after publication

| URL | Behavior |
| --- | --- |
| https://monicarenneke.github.io/ | Minimal homepage |
| https://monicarenneke.github.io/dexian.pdf | Opens GitHub-hosted Dexian PDF directly |
| https://monicarenneke.github.io/mphasis.pdf | Opens GitHub-hosted Mphasis PDF directly |
| https://monicarenneke.github.io/samples.pdf | Opens GitHub-hosted LinkedIn portfolio PDF directly |
| https://monicarenneke.github.io/samples/ | **Learning test:** redirects on the same GitHub Pages site to `/samples.pdf` |

The uploaded PDFs are byte-for-byte copies of their approved Google Drive versions; only the filenames used on GitHub are shorter. The original PDFs remain in `WritingSamples-PUBLIC` and retain their existing URLs.

## Install with Git Bash (Windows)

1. Sign into GitHub as `monicarenneke`. Create the **public** repository `monicarenneke.github.io` with an initial README, unless it already exists.
2. In Git Bash:

   ```bash
   cd ~/git
   git clone https://github.com/monicarenneke/monicarenneke.github.io.git
   cd monicarenneke.github.io
   ```

   If it was already cloned, **do not clone again**. Instead run `cd ~/git/monicarenneke.github.io` and `git status`.
3. Extract this ZIP to a temporary folder such as Downloads. Copy **the seven contents of the ZIP**, not the enclosing folder, into the cloned `monicarenneke.github.io` directory. Replace the placeholder README if prompted. Inspect unexpected existing project files before overwriting.
4. In Git Bash, inside `~/git/monicarenneke.github.io`, run:

   ```bash
   git status
   git add .nojekyll README.md index.html dexian.pdf mphasis.pdf samples.pdf samples/index.html
   git commit -m "Publish approved writing samples on GitHub Pages"
   git push origin main
   ```
5. In GitHub repository **Settings > Pages**, select **Deploy from a branch**, then `main` and `/(root)`, and Save (unless Pages is already configured).
6. Open the five URLs above in an incognito browser after publishing. Compare the two samples URLs, download PDFs, and test the embedded documentation hyperlinks. Do not put the GitHub URLs on resumes until tested.

## File structure

```text
.nojekyll
README.md
index.html
dexian.pdf
mphasis.pdf
samples.pdf
samples/
  index.html
```

## Publication safeguards

- The repository and all its commits will be publicly visible. Never commit unpublished drafts, credentials, confidential information, or source Google Docs. Public versions of a PDF remain retrievable from prior commits even if the filename is later replaced.
- Google Drive `WritingSamples-PUBLIC/Dexian`, `/Mphasis`, and `/LinkedIn` and their approved shared links remain **unchanged**. Keep them available for previously distributed resumes and the LinkedIn Featured item.
- For revisions, preserve historical distributed PDFs according to the portfolio publishing rules. Log newly published GitHub links in the active `Monica — Job Search & Portfolio Tracker` after successful live verification.
