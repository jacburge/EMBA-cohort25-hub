# EMBA Cohort 25 Hub

A multi-page website built for the University of Maryland Robert H. Smith School of Business EMBA Cohort 25 graduation banquet (May 2026).

**Live site:** [jaclynfieldmath.ai/EMBA-cohort25-hub](http://jaclynfieldmath.ai/EMBA-cohort25-hub/)

## Pages

### Landing Page (`index.html`)

The central hub accessed via QR code at the banquet. Features:

- Rotating panoramic class photo banner with slow pan effect and click-to-zoom lightbox
- Navigation cards linking to each section of the site
- Class portrait photo
- Clean, modern design with UMD branding

### By the Numbers (`stats.html`)

An animated presentation celebrating the EMBA Cohort 25 journey through data.

| # | Title | Content |
|---|-------|---------|
| 0 | **EMBA Cohort 25** | Title card |
| 1 | **Who We Are** | Cohort demographics — industry and seniority breakdowns by percentage |
| 2 | **What We Signed Up For** | Hero numbers — assignments, class hours, pages read, hotel nights, credits, days on campus, courses, professors, group projects |
| 3 | **How We Spent Our Weeknights** | Assignment highlights + donut chart of work split by category |
| 4 | **The Courses That Kept Us Up** | Top 10 courses by total Canvas assignments |
| 5 | **Our Most Well-Read Subjects** | Pages read by course |
| 6 | **Professors with the Most Face Time** | Lollipop chart of in-class hours per professor |
| 7 | **The MBA Vocabulary** | Word cloud from course readings, lecture slides, and materials |
| 8 | **Congratulations, Cohort 25!** | Closing slide |

**Desktop:** Auto-plays through all slides with animated charts, counters, and transitions. Keyboard controls: `Space` pause/resume, `←`/`→` navigate, `R` restart.

**Mobile:** Snap-scroll slides with staggered scroll-reveal animations — swipe between full-screen slides like Stories.

### The Class Song (`song.html`)

Listen to the Cohort 25 theme song with embedded audio players for the original and LaMar Isaac's cover. Includes full lyrics with credits to Senthil Govindarajan (lyrics & production) and LaMar Isaac (cover performance).

## Features

- **No build step** — all pages are self-contained HTML files
- **Responsive** — desktop auto-play presentation + mobile snap-scroll with scroll-triggered animations
- **UMD branding** — Maryland red (#E21833) and gold (#FFD200) palette throughout
- **Geist font** — loaded from Fontsource CDN
- **Panoramic photo viewer** — slow pan + blur-fade transitions + click-to-zoom lightbox
- **Embedded audio** — HTML5 audio players for the class song

## Data Sources

- **Canvas assignment tracker** — Excel spreadsheet tracking all 344 assignments across 19 courses
- **Weekend calendar documents** — DOCX files for each in-person session, parsed for class hours and professor attribution
- **Notion class notes** — cross-referenced for professor-to-session mapping
- **Course materials** — PDFs, PPTX slides, and DOCX readings (~290 files, 10M+ characters) processed for the word cloud
- **Cohort directory** — titles and organizations used for demographics (shown as percentages only)

## Credits

Made with ♡ by Jaclyn Mathai
