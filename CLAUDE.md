# Sirivennela Sahityam

Lyrics collection and exploration site for Sirivennela Seetharama Sastry's work.

## Target
- Domain: sirivennelasahityam.com (available as of 2026-02-07)
- Hosting: GitHub Pages (free)
- Design: simple, text-focused, inspired by bollymeaning.com

## Tech
- Static site generator (Hugo or Jekyll)
- GitHub Pages for hosting
- Custom domain via CNAME record
- Firebase/Supabase free tier for community feedback data (vote counts)

## Feature Ideas
- **Community-weighted lyrics**: Users select lines/portions that resonate with them. Over time, popular lines render in bold or larger font based on aggregate response.
- **View toggle**: Switch between static (plain) view and feedback-weighted view.
- Architecture: static site + client-side JS calls to Firebase/Supabase API for read/write. No backend server needed.

## Design Preferences
- **Telugu font**: Noto Sans Telugu (Google Fonts) — clean, readable, well-maintained
  - Alternative for literary feel: Noto Serif Telugu
- **Responsive**: Must work seamlessly on both desktop and mobile
- **Mobile UX**: Tap-to-highlight for community voting (not hover-based)

## Status
Someday project — tracked from `~/Gits/nirdeshi/projects_ideas/someday.md`

## Related
- Tracked from nirdeshi: `~/Gits/nirdeshi/`
