# AGENTS.md — Rules for working on this site

Site owner: Anisha Kaul. Site: personal home page (GitHub Pages, `anishatkaul.github.io`).
Source of truth for content: `resume.pdf`. LinkedIn: linkedin.com/in/anishatkaul. GitHub: github.com/anishatkaul.

## Never publish
- Phone number, home address, birthday, or any other personal ID.
- Email address, unless Anisha explicitly approves the specific address to show.
- `resume.pdf` itself (it contains her phone number). Do not link to it, copy it, or commit it to a public repo unless a redacted version is approved.
- Anything not in her CV or approved by her: no invented metrics, titles, dates, employers, quotes, testimonials, or projects.
- Confidential employer information beyond what her CV already states.
- Credentials, API keys, tokens, or analytics/tracking IDs.
- Third-party images, logos, or fonts without a clear license (no company logos).

## Ask first
- Before any `git push`, `git commit` to a shared branch, deploy, or any other action that makes the site public. Local work only by default.
- Before adding any contact detail (email, phone, social account) beyond LinkedIn and GitHub.
- Before adding content that is not in the CV (bio text, projects, photos, blog, testimonials).
- Before rewording CV facts in a way that changes meaning, numbers, or titles.
- Before adding third-party scripts, trackers, fonts loaded from CDNs, or external dependencies.
- Before deleting or overwriting any existing file.
- Before changing the section order (Education → Experience → Additional Information).


## Style
- Tone: professional and casual. Warm, plain-spoken, no buzzword stuffing.
- Palette: Columbia blue (`#B9D9EB`) with deep navy text and a darker blue accent for contrast. Keep text contrast at WCAG AA or better.
- Layout: clean and modern; sticky, minimal navigation; tiles/cards for scannable content.
- Content: faithful to the CV, same section order, same facts and numbers.
- Tech: static, single-file HTML/CSS/JS where possible; no build step, no external requests.
- Accessible and responsive: semantic HTML, keyboard-navigable, visible focus, respects `prefers-reduced-motion`, works on mobile.
- Report honestly: when finishing, list every file created and anything intentionally left out.
## When you finish
- Tell me what you changed and what you skipped
