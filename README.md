# portfolio-template

A small collection of free, open-source portfolio templates for developers. Fork one, fill in your info, and ship it. No frameworks, no build steps, no subscriptions.

by [kay](https://kayspace.vercel.app) — contributions are welcome.

---

## templates

| # | name | style | status |
|---|------|-------|--------|
| 01 | [Template 1](templates/template1.html) | dark, monospace-first, minimal | live |
| 02 | [Template 2](templates/template2.html) | light, warm paper tones, serif headings | wip |
| 03 | [Template 3](templates/template3.html) | light, bold | archived |

---

## structure

```
portfolio-template/
├── index.html           ← homepage 
├── templates/           ← templates folder
│   ├── template1.html   
│   └── template2.html   
│   └── template3.html  
├── LICENSE
├── CONTRIBUTING.md
└── README.md
```

---

## getting started

**1. fork or clone**

```bash
git clone git@github.com:kayspace/portfolio-template.git
cd portfolio-template
```

**2. pick a template**

Open `templates/template1.html` or `templates/template2.html` in your editor. Every placeholder is clearly marked in brackets — for example:

```
[Your Name]
[your.email@domain.com]
[Your Description]
```

Replace them with your own content. That is all there is to it.

**3. deploy**

Each template is a single self-contained `.html` file. You can deploy it anywhere that serves static files:

- **Vercel** — drag and drop the folder or connect your forked repo
- **Netlify** — same as above
- **GitHub Pages** — push to a repo and enable Pages in settings

No build process, no `npm install`, no config files.

---

## customising

Both templates use CSS custom properties (variables) at the top of the `<style>` block. Changing colors, fonts, or spacing is straightforward — look for the `:root { }` block and edit from there.

Each template also includes comments explaining what each section does.

---

## contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Want to add a template or improve an existing one? Contributions are welcome.

1. Fork the repo
2. Create a new branch — `git checkout -b add/template3`
3. Add your template to `templates/template3.html`
4. Update the template list in `index.html` and this README
5. Open a pull request

A few things that make a good template contribution:

- Self-contained single `.html` file — styles and scripts inline
- No external dependencies other than Google Fonts and optionally GSAP (both CDN)
- All placeholder text in `[brackets]` so users know exactly what to replace
- Works on mobile without extra effort

---

## Support

- Open an [issue](https://github.com/kayspace/portfolio-template/issues) for bugs
- Start a [discussion](https://github.com/kayspace/portfolio-template/discussions) for questions

## licence

MIT — free to use, modify, and distribute for personal and commercial projects. You do not need to credit me, but a note in your footer or a star on this repo is genuinely appreciated.

See [LICENSE](LICENSE) for the full text.

---

*if u like it, [star the repo](https://github.com/kayspace/portfolio-template) :)*