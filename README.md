# sidharthsahoo.github.io

// one file. one photo. zero website builders.  
// my personal site — agentic AI engineer, production systems, not demo theater.

**Live:** [sidharthsahoo.github.io](https://sidharthsahoo.github.io) *(once you actually deploy it)*

---

## what this is

A single-page portfolio hand-coded in `index.html`. No React, no Next, no "drag your hero section here" nonsense. Just HTML, CSS, and ~30 lines of vanilla JS that do nav toggles, scroll reveals, and stat count-ups.

The pitch on the page: I turn *"you think it"* into *"I built it."* Multi-agent AI systems that survive contact with production. Seven years shipping software; the last two making agents behave when it counts.

---

## repo contents

```
.
├── index.html      # the entire site. yes, all of it.
├── profile.jpg     # square headshot (optional — initials fallback if missing)
└── README.md       # you are here
```

That's it. Backend person's dream repo structure.

---

## deploy (free, ~2 minutes)

1. Push this repo to GitHub. Name it `sidharthsahoo.github.io` if you want the clean URL, or any repo name if you don't care.
2. Drop `index.html` at the repo root.
3. Drop a square photo next to it named `profile.jpg`. Skip it if you want the `SS` initials tile instead — still looks fine.
4. **Settings → Pages → Deploy from branch → `main` / root.**
5. Wait a minute. GitHub gives you a URL. Paste that into LinkedIn's "Add website" field. Link text max 30 chars — `"What I build"` works.

// no domain required. GitHub Pages is free. you're welcome.

---

## before you go live — swap the placeholders

| What | Where | Current value |
|------|-------|---------------|
| GitHub handle | `index.html` (2× links) | `your-handle` |
| Email | hero + contact | `sidharthsahoodev@gmail.com` |
| Phone | contact section | `+91 98105 57721` |
| LinkedIn | hero + contact | already set |
| Photo | `profile.jpg` | add your own square crop |

Search `your-handle` in `index.html` and replace. Everything else is already me — edit the copy if you're forking this for yourself. *(Please don't just deploy my life story with your face on it. That's weird.)*

---

## sections on the page

| Section | ID | What's in it |
|---------|-----|--------------|
| Hero | `#top` | Tagline, CTAs, live-status console, photo |
| About | `#about` | Short version + education |
| Stats | — | Animated counters. Career by the numbers. |
| Now | `#now` | PACCA AI — what I'm building at Emids |
| Journey | `#journey` | Timeline: Emids → Turbostart → ENITIATE → … |
| Beyond work | `#beyond` | Side projects nobody asked for |
| Skills | `#skills` | Toolkit + how I actually work |
| Trivia | `#trivia` | CV overflow — the human bits |
| Contact | `#contact` | Email, LinkedIn, GitHub, phone |

// note: `#platform` exists in the nav scrollspy but the section is commented out in HTML.  
// uncomment lines 335–361 in `index.html` if you want the full PACCA platform breakdown.

---

## tech stack (for the site itself)

- **Fonts:** Bricolage Grotesque, Hanken Grotesk, JetBrains Mono (Google Fonts CDN)
- **JS:** IntersectionObserver for reveals + scrollspy, `requestAnimationFrame` for count-ups
- **CSS:** Custom properties, no preprocessor, no framework
- **Dependencies:** None. Zero `npm install`. Zero `package.json`. Zero regrets.

// I am a backend person. Be kind about the CSS. It works.

---

## local preview

No build step. Open the file:

```bash
open index.html
```

Or serve it if you want anchor links and fonts to behave like production:

```bash
python3 -m http.server 8080
# then http://localhost:8080
```

---

## contact

Building something ambitious with LLMs and agents? Say hi.

- **Email:** sidharthsahoodev@gmail.com
- **LinkedIn:** [linkedin.com/in/sidharthsahoo](https://www.linkedin.com/in/sidharthsahoo)
- **Phone:** +91 98105 57721

Open to senior AI engineering and solutions-architecture roles worldwide. Visa sponsorship welcome — I make that part easy.

---

*// hand-coded. no template. no AI-generated layout.*  
*// execution separates the dreamers from the doers.*
