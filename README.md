# Mindful Moments

## Introduction
This project aims to create a beginner-friendly and supportive mental health awareness website. The primary goal is to provide accessible, clear, and actionable information on mental well-being, common issues, and effective stress management techniques. The design prioritizes a calm, clean, and well-organized user experience.

A responsive site layout enables easy navigation on all devices.

### Technical Focus
The website is built using HTML5 and styled with CSS leveraging the Bootstrap framework (version 5.x) to ensure a modern, responsive, and aesthetically pleasing design. We will focus on utilizing Bootstrap components to deliver a supportive and visually appealing layout.

### Key Features & Components
- Hero Section (Bootstrap Jumbotron/Custom Section): A prominent, calming introduction  about mental health, set against a simple, soothing background and colour palette.

- Information Cards (Bootstrap Cards): Content will be broken down into digestible sections using visually distinct cards. These will cover topics like:

     - Simple Stress Management Techniques
     - Everyday Wellness Tips

- Resource Links (Bootstrap Grid & Buttons): A dedicated section will feature external links to credible mental health organizations and helplines. Links will be presented in a clear grid layout and styled with Bootstrap buttons for high visibility and easy access.

- Positive Affirmations/Uplifting Quotes: A dedicated area using Bootstrap's text and utility classes to display uplifting and encouraging quotes or messages to provide a continuous source of motivation and support for the user.

- Contact section is provided in the footer with contact information and key social media links

## Desktop

<img width="1906" height="697" alt="image" src="https://github.com/user-attachments/assets/1b0b5117-1cd2-4660-838e-17e8f76c34ff" />

## Tablet

<img width="733" height="887" alt="image" src="https://github.com/user-attachments/assets/af0fa5a6-6a83-4eca-ac83-c9cfe79a7c1e" />


## Mobile

<img width="745" height="905" alt="image" src="https://github.com/user-attachments/assets/f9ecd38f-1ffb-4ca6-8923-2a969c13397a" />

## UX Design
### Typography

Font Awesome icons were used for the site icons. For example, the social media icons in the footer of the pages.

Comic Relief was used for the font.

## Wireframe Design

<img width="522" height="768" alt="image" src="https://github.com/user-attachments/assets/87b0e6bb-2b6f-4369-a48c-5d54f2d88f34" />


<img width="296" height="498" alt="image" src="https://github.com/user-attachments/assets/62fd4f79-f449-46df-9695-c13ede88da20" />


<img width="238" height="425" alt="image" src="https://github.com/user-attachments/assets/ef4bada0-f54b-4b71-a37d-25666aa14729" />








## User Stories (Simple)

Goal: Provide beginner-friendly mental health information in a calm, supportive layout using HTML, CSS, and Bootstrap.

1) Navigation — As a user, I want simple, consistent navigation that adapts to screen size so I can find key pages quickly.
	- Acceptance Criteria

      - The website is fully responsive across various devices and screen sizes.
      - Site layout and navigation are simple, allowing easy access to different sections.
      
    - Tasks

      - Apply responsive design principles using Bootstrap to ensure the website is accessible on various devices.
      - Arrange the site layout and navigation based on best practices, ensuring all key sections and pages are easily accessible.

2) Hero Section with Positive Messaging - As a visitor, I want a calming hero with a positive message and clear buttons so I know where to start.

	- Acceptance criteria:
	  - Hero shows a supportive headline, short subheading, and CTAs for Learn, Manage Stress, and Find Help.
	  - Responsive on mobile/desktop with readable contrast; background image is decorative (no critical info).
	- Tasks:
	  - Add a hero section to `index.html` with roomy spacing.
	  - Use calm colours and (optional) a simple background image.

3) Information Cards — As a beginner, I want information cards about common issues (e.g., anxiety, depression, stress) so I can recognise signs.
	- Acceptance criteria:
	  - A grid of cards presents a plain-language summary, 3–5 common signs.
	  - Cards are readable on mobile and desktop; links use descriptive text.
	- Tasks:
	  - Make a grid of Bootstrap cards.
	  - Write short, beginner-friendly text for all topics.

4) Resource links — As a user in crisis, I want a prominent "Find Help" area so I can access hotlines and resources right away.
	- Acceptance criteria:
	  - Resource links are styled as buttons; open in new tab with `rel="noopener"` and accessible labels.
	- Tasks:
	  - Create resources section using a grid of buttons for help links.
	  - Open external links in a new tab safely; add clear labels where useful.
	  - Make the most important resources stand out.

5) Positive Affirmations — As a visitor, I want a short section of positive affirmations so I feel encouraged.
	- Acceptance criteria:
	  - A small list of uplifting messages uses Bootstrap text utilities for clear, calm presentation.
	- Tasks:
	  - Add an affirmations section to `index.html` below the cards.
	  - Write 5–7 short, supportive lines.
	  - Style with simple Bootstrap text and spacing classes.

6) Accessibility — As an accessibility user, I want the site to be easy to navigate with a keyboard and screen reader.
	- Acceptance criteria:
	  - Semantic landmarks (`header`, `nav`, `main`, `footer`) and logical heading order (one H1 per page).
	  - All interactive elements are reachable by keyboard with visible focus; images have appropriate `alt`.
	- Tasks:
	  - Use header, nav, main, and footer, with clear headings.
	  - Add alt text to images and make sure focus styles are visible.
	  - Do a quick check with a tool (e.g., Lighthouse) and by using only the keyboard.

7) Footer — As a visitor, I want a clear footer with quick links and help info so I can find key pages and support easily.
	- Acceptance criteria:
	  - Footer shows links to key pages (social media links).
	  - Includes a small "Contact ussection".
	  - Looks good on small and large screens; link focus is visible; contrast is readable.
	- Tasks:
	  - Add a footer section to pages using a Bootstrap container/row.
	  - Add quick links and a small crisis/help note.
	  - Make sure external help links open safely in a new tab.

## Testing
### Lighthouse
The site was tested using Lighthouse with the following results: 
<img width="698" height="708" alt="image" src="https://github.com/user-attachments/assets/c91fdab2-1e29-4b2e-8a2d-554d4274b502" />

### Responsive Testing
Alongside the built in Bootstrap responsive CSS, Chrome dev tools were used frequently to test the site at standard screen sizes and the site was manually viewed on laptops, tablets and phones.
### Validator Testing
 - HTML
   - No errors were returned when passing through the official W3C validator
    <img width="1756" height="840" alt="image" src="https://github.com/user-attachments/assets/c819e808-b274-43a3-8001-5ca4b109e47a" />


 - CSS
   - No errors were found with our own CSS code
    <img width="1774" height="873" alt="image" src="https://github.com/user-attachments/assets/ed7b86a0-599a-45fc-9b8c-154c6b951bdc" />

