# MentalHealthAwareness
A mental health awareness project aims to educate the community, reduce stigma and discrimination, and promote positive mental well-being by fostering open conversations and ensuring people know that help is available.

## User Stories (Simple)

Goal: Provide beginner-friendly mental health information in a calm, supportive layout using HTML, CSS, and Bootstrap.

1) Navigation — As a user, I want simple, consistent navigation that adapts to screen size so I can find key pages quickly.
	- Acceptance criteria:
	  - Navbar collapses with a Bootstrap toggler on small screens; links are keyboard/touch accessible.
	  - Includes a visible-on-focus skip link to `#main`; focus states are clearly visible.
	- Tasks:
	  - Add a Bootstrap navbar that collapses on small screens.
	  - Add a skip link to go straight to the main content.
	  - Check that keyboard users can move through the links and see the focus.

2) Hero Section with Positive Messaging
	- User story: As a visitor, I want a calming hero with a positive message and clear buttons so I know where to start.
	- Acceptance criteria:
	  - Hero shows a supportive headline, short subheading, and CTAs for Learn, Manage Stress, and Find Help.
	  - Responsive on mobile/desktop with readable contrast; background image is decorative (no critical info).
	- Tasks:
	  - Add a hero section to `index.html` with roomy spacing.
	  - Use calm colours and (optional) a simple background image.
	  - Link the buttons to Learn, Manage, and Resources pages/sections.

3) Information Cards — As a beginner, I want information cards about common issues (e.g., anxiety, depression, stress) so I can recognise signs.
	- Acceptance criteria:
	  - A grid of cards presents a plain-language summary, 3–5 common signs, and a "When to seek help" note.
	  - Cards are readable on mobile and desktop; links use descriptive text.
	- Tasks:
	  - Make a grid of Bootstrap cards.
	  - Write short, beginner-friendly text for at least 3 topics.
	  - Add optional "Read more" links to deeper pages/sections.

4) Stress Techniques — As a user, I want quick stress‑management techniques so I can try them immediately.
	- Acceptance criteria:
	  - Techniques are shown in simple steps using cards or an accordion.
	  - Core content usable without audio or JavaScript; print-friendly tip available.
	- Tasks:
	  - Create `manage.html` and list 3–5 techniques in an accordion or cards.
	  - Avoid heavy animations; respect reduced‑motion settings.
	  - Add simple print styles so one page of tips prints cleanly.

5) Find Help — As a user in crisis, I want a prominent "Find Help" area so I can access hotlines and resources right away.
	- Acceptance criteria:
	  - A crisis banner appears at the top with clear wording and key numbers/links.
	  - Resource links are styled as buttons; open in new tab with `rel="noopener"` and accessible labels.
	- Tasks:
	  - Create `resources.html` with a crisis banner at the top and a grid of buttons for help links.
	  - Open external links in a new tab safely; add clear labels where useful.
	  - Make the most important resources stand out.

6) Positive Affirmations — As a visitor, I want a short section of positive affirmations so I feel encouraged.
	- Acceptance criteria:
	  - A small list of uplifting messages uses Bootstrap text utilities for clear, calm presentation.
	  - No auto-advancing carousels; minimal motion and good contrast.
	- Tasks:
	  - Add an affirmations section to `index.html` below the cards.
	  - Write 5–7 short, supportive lines.
	  - Style with simple Bootstrap text and spacing classes.

7) Accessibility — As an accessibility user, I want the site to be easy to navigate with a keyboard and screen reader.
	- Acceptance criteria:
	  - Semantic landmarks (`header`, `nav`, `main`, `footer`) and logical heading order (one H1 per page).
	  - All interactive elements are reachable by keyboard with visible focus; images have appropriate `alt`.
	  - Body text contrast ratio ≥ 4.5:1.
	- Tasks:
	  - Use header, nav, main, and footer, with clear headings.
	  - Add alt text to images and make sure focus styles are visible.
	  - Do a quick check with a tool (e.g., Lighthouse) and by using only the keyboard.

8) Maintenance — As a site owner, I want a simple structure so I can update content quickly.
	- Acceptance criteria:
	  - Clear file layout (HTML pages + `assets/css/styles.css`) and Bootstrap via CDN.
	  - Minimal custom JS; content sections are clearly commented for easy edits.
	- Tasks:
	  - Create base files: `index.html`, `manage.html`, `resources.html`, `about.html`, `contact.html`, `learn/index.html`, `assets/css/styles.css`.
	  - Add Bootstrap via CDN and include the viewport meta tag.
	  - Add a short note about the structure in this README.

9) Footer — As a visitor, I want a clear footer with quick links and help info so I can find key pages and support easily.
	- Acceptance criteria:
	  - Footer shows links to key pages (Home, Learn, Manage, Resources, About, Contact).
	  - Includes a small "Find help now" link or hotline highlight.
	  - Looks good on small and large screens; link focus is visible; contrast is readable.
	- Tasks:
	  - Add a footer section to pages using a Bootstrap container/row.
	  - Add quick links and a small crisis/help note.
	  - Make sure external help links open safely in a new tab.

Notes
- Use Bootstrap components: Navbar, Cards, Accordion, Buttons, Grid, and spacing/typography utilities.
- Keep a calming color palette, plain language, and minimal motion (respect reduced‑motion preferences).
