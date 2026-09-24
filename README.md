# My CV / Resume

A single-page CV/resume for Fady Ehab Amer, built with plain HTML and CSS. It has a two-column layout: contact details, skills and social links on the left, and about, work experience, education and hobbies on the right.

## Project structure

```
Resume-CV-Design-N19-master/
├── index.html   # resume markup
├── styles.css   # layout and styling
└── fady.jpg     # profile photo
```

## Viewing it

No build step or dependencies are needed. Open `Resume-CV-Design-N19-master/index.html` in a browser, or serve the folder locally:

```bash
git clone https://github.com/fadyehabamer/My-CV-Resume.git
cd My-CV-Resume/Resume-CV-Design-N19-master
python3 -m http.server 8000
# then visit http://localhost:8000
```

Icons (Font Awesome) and the Montserrat font (Google Fonts) load from CDNs, so you need an internet connection for them to show.

## Customising

Edit the text in `index.html` to update your details. Skill bars are set with the inline `width` on each `.skill_progress span`, and the colour scheme is in `styles.css`.

## License

See [LICENSE](LICENSE).
