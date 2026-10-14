# Ayush Yadav — portfolio site

Single-page portfolio. Plain HTML, no build step, no dependencies to install.

```
index.html      the whole site (CSS and JS inline)
resumes/        16 role-specific resumes, linked from the Resumes section
```

## Deploy on GitHub Pages

1. Create a new **public** repository on GitHub. Name it `ayush-yadav`
   (or name it `<your-username>.github.io` if you want the short root URL).
2. On the repo page: **Add file → Upload files**. Drag in `index.html`,
   the `resumes` folder and this README. Commit.
3. **Settings → Pages**. Under *Build and deployment*, set
   Source = `Deploy from a branch`, Branch = `main`, folder = `/ (root)`. Save.
4. Wait about a minute, then reload the Pages settings screen. Your live URL
   appears at the top:
   - `https://<username>.github.io/ayush-yadav/` for a normal repo
   - `https://<username>.github.io/` if you used the `<username>.github.io` name

That URL is public. Anyone you send it to can open it — no GitHub account needed.

## Editing it later

Everything is in `index.html`. The colour palette is the `:root` block at the
top of the `<style>` tag; change a token there and it updates everywhere, in
both light and dark mode.

To swap a resume, replace the PDF in `resumes/` keeping the same filename —
the link on the page keeps working.

## Custom domain (optional)

Buy a domain, then in **Settings → Pages → Custom domain** enter it and add
the DNS records GitHub shows you. `ayushyadav.in` or similar reads better on
a resume than a github.io URL.
